# Kombinatorika

## Faktoriál

\[ \begin{align}
n! &= n \cdot (n-1) \cdot (\ldots) \cdot 1
\end{align} \]

## Permutace

\[ \begin{align}
P(n) &= n! \\
P^\ast\!(n_1, n_2, \ldots, n_x) &= \frac{\left(\sum_{i=1}^x n_i \right)!}{\prod_{i=1}^x n_i!} \\
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
C^\ast\!(n, k) &= {n + k - 1 \choose k} = \frac{(n+k-1)!}{(n-1)! \cdot k!}
\end{align} \]

## Vztahy mezi funkcemi

\[ \begin{align}
V(n, n) &= P(n) \\
V(n, n-1) &= P(n) \\ \\
C(n, k) &= \frac{V(n, k)}{P(k)} \\ \\
C^\ast\!(n, k) &= C(n+k-1, k) \\
C^\ast\!(n, k) &= P^\ast(n-1, k)
\end{align} \]
