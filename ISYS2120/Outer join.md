OUTER JOIN produces a resulting join tuple even if there is no join partner available in one of the input relations. Returns NULL values on the corresponding side.

`r1 LEFT OUTER JOIN r2`
Keep all input tuples of r1 even if there is no join partner from r2

`r1 RIGHT OUTER JOIN r2`
Keep all input tuples of r2 even if there is no join partner from r1

`r1 OUTER JOIN r2`
Keep all input tuples of both,
