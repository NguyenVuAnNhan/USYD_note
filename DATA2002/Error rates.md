| Outcomes                        | Truth: $\theta = 0$ | Truth: $\theta \neq 0$ | Number of tests |
| ------------------------------- | ------------------- | ---------------------- | --------------- |
| **Conclusion:** $\theta = 0$    | $U$                 | $T$                    | $m - R$         |
| **Conclusion:** $\theta \neq 0$ | $V$                 | $S$                    | $R$             |
| **Number of tests**             | $m_0$               | $m-m_0$                | $m$             |

Family wise error rate (FWER):
$$FWER = P(V\ge 1)$$

Bonferroni correction:
$$\alpha^*=\frac{a}{m}$$
- Conservative but keeps FWER $\le \alpha$
- Defined as the new threshold for significance
- Pros: easy to calculate
- Cons: very conservative

False discovery rate (FDR):
$$FDR = E(\frac{V}{R})$$

Benjamini - Hochberg procedure:
- Do $m$ tests, control FDR at level $\alpha$
- Calculate p-values normally
- Order the p-values from smallest to largest $p_{(1)} \le p_{(2)} \le ... \le p_{(m)}$
- Find $j^* = max j$ such that $p_{(j)} \le \frac{j}{m}\alpha$
- Reject all $H_{0i}$ where $p_{(i)} \le \frac{j^*}{m}\alpha$
- Pros: easy to calculate, less conservative
- Cons: more false positive, strange behaviors under dependence