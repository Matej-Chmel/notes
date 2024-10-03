# Náhodná veličina

Přiřazuje každému elementárnímu jevu $\omega$ reálné číslo. Existují dva druhy &mdash; diskrétní a spojitá.

Diskrétní může nabývat *spočetně mnoha hodnot*. Spojitá všech hodnot na nějakém intervalu.

\[ \begin{align}
(X = a) &= \{ \omega \in \Omega: &X(\omega) = a \} \\
(X < a) &= \{ \omega \in \Omega: &X(\omega) < a \} \\
(X > a) &= \{ \omega \in \Omega: &X(\omega) > a \} \\
(a < X < b) &= \{ \omega \in \Omega: &a < X(\omega) < b \}
\end{align} \]

Náhodnou veličinu lze popsat funkcemi &mdash; pravděpodobnostní, distribuční a hustotou pravděpodobnosti. Tyto funkce lze zapsat:

- předpisem
- tabulkou
- grafem

## Pravděpodobnostní funkce

Pravděpodobnost, že náhodná veličina nabývá dané hodnoty.

\[ \begin{align}
P(x_i) &\geq 0 \\
\sum_i^{\left| \Omega \right |} P(X = x_i) &= 1
\end{align} \]

## Distribuční funkce

Pravděpodobnost, že náhodná veličina bude menší než dané číslo.

### Vlastnosti

- klesající
- zleva spojitá
- má nejvýše početně mnoho bodů nespojitosti
- začíná v 0 (viz 2)
- končí v 1 (viz 3)

\[ \begin{align}
0 \geq F(t) &\geq 1 \\ \\
\lim_{t \to -\infty} F(t) &= 0 \label{eq:2} \\ \\
\lim_{t \to \infty} F(t) &= 1 \label{eq:3}
\end{align} \]

### Diskrétní náhodná veličina

Je nespojitá.

\[ \begin{align}
F(t) &= P(X < t)
\end{align} \]

Pokud známe $F(t)$, dokážeme odvodit $P(t)$.

#### Suma

\[ \begin{align}
\sum_{x_i < t} P(X = x_i)
\end{align} \]

#### Body nespojitosti

Body nespojitosti distribuční funkce jsou body, v nichž je pravděpodobnostní funkce nenulová.

\[ \begin{align}
P(X = a) &= \lim_{x \to a^+} F(x) - F(a)
\end{align} \]

Velikost "skoku" distribuční funkce je rovna příslušným hodnotám pravděpodobnostní funkce.

### Spojitá náhodná veličina

Charakterizována *hustotou pravděpodobnost* $f(x)$
Je spojitá.

\[ \begin{align}
F(t) &= \int_{-\infty}^t f(x) dx
\end{align} \]

## Vztahy mezi distribuční a pravděpodobnostní funkcí

\[ \begin{align}
P(X < a) &= F(a) \\
P(X \geq a) &= 1 - P(X < a) &= F(a) \\
P(a \leq X < b) &= P(X < b) - P(X < a) &= F(b) - F(a) \\
P(X = a) &= \lim_{x \to a^+} F(x) - F(a)
\end{align} \]
