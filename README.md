# MathJax in github?

\[ P(E) = {n \choose k} p^k (1-p)^{ n-k} \]

```

Pr(n0, n1, n2, n3|a, b, c, d) = a^2n0 . (2ab + 2ad)^n1 + (b^2 + 2ac + 2bd + d^2)^n2 + (c^2 + 2bc + 2cd)^n3

```

\[
Pr(n_0, n_1, n_2, n_3|a, b, c, d) = a^{2n_0} . (2ab + 2ad)^{n_1} + (b^2 + 2ac + 2bd + d^2)^{n_2} + (c^2 + 2bc + 2cd)^{n_3}
\]



This would be a straightforward application of Bayes' rule:

```
Pr(carrier|2-copy) = Pr(carrier, 2-copy) / Pr(2-copy) = [Pr(0+2) + Pr(0+1d)] / [Pr(0+2) + Pr(0+1d) + Pr(1+1)]
```

\[
Pr(\texttt{carrier}|\texttt{2 copies}) = \frac{ Pr(0+2) + Pr(0+1d) }{ Pr(0+2) + Pr(0+1d) + Pr(1+1) }
\]

