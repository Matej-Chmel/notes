# Kombinatorika

## Faktoriál

\[ \begin{align}
n! &= n \cdot (n-1) \cdot (\ldots) \cdot 1
\end{align} \]

## Permutace

\[ \begin{align}
P(n) &= n! \\
P^\ast\!(a, b, c) &= \frac{(a + b + c)!}{a! \cdot b! \cdot c!} \\ \\
P(n) &= V(n, n)
\end{align} \]

## Variace

\[ \begin{align}
V(n, k) &= \frac{n!}{(n-k)!} \\
V^\ast\!(n, k) &= n^k
\end{align} \]

## Kombinace

\[ \begin{align}
C(n, k) &= {n \choose k} \\ \\
{n \choose k} &= \frac{n!}{(n-k)! \cdot k!} \\ \\
C^\ast\!(n, k) &= {n + k - 1 \choose k} \\ \\
{n + k - 1 \choose k}  &= \frac{(n+k-1)!}{(n-1)! \cdot k!} \\ \\
C^\ast\!(n, k) &= P^\ast(n-1, k)
\end{align} \]