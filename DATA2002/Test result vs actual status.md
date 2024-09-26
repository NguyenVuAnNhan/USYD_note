| Test\True          | positive $D^+$     | negative $D^-$     |
| ------------------ | ------------------ | ------------------ |
| **positive** $S^+$ | True positive (a)  | False positive (b) |
| **negative** $S^-$ | False negative (c) | True negative (d)  |

Accuracy: the probability that the test is correct
$$Acc = \frac{a+d}{a+b+c+d}$$
Misclassification rate: the probability to get incorrect results
$$Miss = \frac{b+c}{a+b+c+d}$$
False negative rate: probability to get false negative given that the true value is positive:
$$FNR = P(S^-|D^+) = \frac{c}{a+c}$$

Sensitivity/recall/true positive rate: get positive when true is positive
$$TPR = 1 - FNR = \frac{a}{a+c}$$
False positive rate: get positive when true is negative
$$FPR = \frac{b}{b + d}$$
Specificity or true negative rate: get negative when true is negative
$$TNR = \frac{d}{b+d}$$
Precision: The probability that true is positive given that test returns positive
$$PRC = P(D^=|S^+) = \frac{a}{a+b}$$
Negative predictive value: The probability that true is negative given that test returns negative
$$NPV = P(D^-|S^-) = \frac{d}{c+d}$$
