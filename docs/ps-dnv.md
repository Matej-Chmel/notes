# Číselné charakteristiky DNV

## Obecný moment

Pro $r$-tý řád.

\[ \begin{align}
\mu_r &= \sum_i x_i^r \cdot P(x_i)
\end{align} \]

## Střední hodnota

Je obecným momentem 1. řádu.

\[ \begin{align}
E(X) &= \sum_i x_i \cdot P(x_i)
\end{align} \]

- průměrná, očekávaná hodnota NV
- populační průměr
- vážený průměr všech hodnot

### Vlastnosti

\[ \begin{align}
E(aX + b) &= aE(x) + b \\ \\
E(\sum_i^n) &= \sum_i^n E(X_i) \\
E(\prod_{i=1}^n X_i) &= \prod_{i=1}^n E(X_i) &\quad \text{nezávislé veličiny}
\end{align} \]

## Modus

Typická hodnota NV.

\[ \begin{align}
P(X = \hat{x}) \geq P(X = x_i)
\end{align} \]

- Modů může být více
- Pokud je jen jeden, pak NV má *unimodální rozdělení*

Pro unimodální *symetrické* rozdělení:

\[ \begin{align}
E(X) &= \hat{X}
\end{align} \]

## Centrální moment

Pro $r$-tý řád.

\[ \begin{align}
\mu_r^\prime &= \sum_i (x_i - E(X))^r \cdot P(x_i)
\end{align} \]

## Rozptyl

Střední kvadratická odchylka od střední hodnoty.

\[ \begin{align}
\mu_2^\prime &= \sum_i (x_i - E(X))^2 \cdot P(x_i) \\
D(X) &= \sigma^2 &= \mu_2^\prime \\
D(X) &= E(X^2) - (E(X))^2
\end{align} \]

- Míra variability kolem střední hodnoty
- Malý rozptyl $\implies$ hodnoty s vysokou pravděpodobností blízko střední hodnoty
- Velký rozptyl $\implies$ hodnoty s vysokou pravděpodobností daleko od střední hodnoty

### Vlastnosti

\[ \begin{align}
D(aX + b) &= a^2 D(X) \\
D(\sum_i^n X_i) &= \sum_i^n D(X_i) &\quad \text{nezávislé veličiny}
\end{align} \]

## Směrodatná odchylka

Odmocnina z rozptylu.

\[ \begin{align}
\sigma(X) &= \sqrt{D(X)}
\end{align} \]

## Variační koeficient

Směrodatná odchylka v procentech střední hodnoty.

\[ \begin{align}
\gamma(X) &= \frac{\sigma(X)}{E(X)} \cdot 100 %
\end{align} \]

- Čím nižší, tím *homogennější* soubor
- Pokud $\gamma(X) > 50 %$, pak silně rozptýlený soubor
