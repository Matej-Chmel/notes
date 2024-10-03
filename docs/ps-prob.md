# Pravděpodobnost

## Pojmy

|Pojem|Význam|
|:--|:--|
|Pokus|Děj, který probíhá, resp. nastává opakovaně za určitých, stejně nastavených, počátečních podmínek.|
|Náhodný pokus|Konečný děj, jehož výsledek není předem jednoznačně určen podmínkami, za nichž probíhá.|
|Náhodný jev|Tvrzení o výsledku náhodného pokusu, o jehož pravdivosti můžeme po ukončení pokusu rozhodnout.|
|Elementární jev ω|Jednotlivý výsledek náhodného pokusu, který nelze vyjádřit jako sjednocení dvou různých jevů.|
|Základní prostor $\Omega$|Množina všech elementárních jevů.|
|Disjunktní jevy|Neslučitelné jevy, které nemohou nastat zároveň.|
|Průnik|𝐴 $\cap$ B|
|Sjednocení|𝐴 $\cup$ B|

## Pravděpodobnost

Číselné vyjádření šance, že vybraný jev nastane.

\[ \begin{align}
P &\in \langle 0; 1 \rangle \\
P(\Omega) &= 1 \\
P(\emptyset) &= 0 \\
P(\overline{A}) &= 1 - P(A) \\
P(A \cup B) &= P(A) + P(B) - P(A \cap B) \\
P(A \cup B) &= P(A) + P(B) &\quad \text{Disjunktní jevy} \\
P(A \cap B) &= P(A|B) \cdot P(B) \\
P(A \cap B) &= P(A) \cdot P(B) &\quad \text{Nezávislé jevy} \\
P(A \cap B) &= 0 &\quad \text{A a B jsou disjunktní}
\end{align} \]

### Klasická definice

Nechť Ω je množina 𝒏 rovnocenných elementárních jevů.
Pravděpodobnost jevu A, jenž je složen z 𝒎 těchto elementárních jevů je:

\[ \begin{align}
P(A) &= \frac{m}{n}
\end{align} \]

### Statistická definice

\[ \begin{align}
P(A) &= \lim_{n \to \infty} \frac{n(A)}{n}
\end{align} \]

$n(A)$ &mdash; počet realizací, kdy jev $A$ nastal

$n$ &mdash; počet všech realizací pokusu

### Geometrická definice

\[ \begin{align}
P(A) &= \frac{|A|}{|\Omega|}
\end{align} \]

## Kolmogorovův axiomatický systém

1. Každému jevu $A$ je přiřazena nezáporná P(A).
2. Pravděpodobnost jevu jistého je $1$.
3. Pravděpodobnost, že nastane některý z navzájem se vylučujících jevů, je rovna součtu jejich pravděpodobností.

\[ \begin{align}
P(\Omega) &= P(\omega_1) + P(\omega_2) + (...) + P(\omega_n) = 1 
\end{align} \]

## Podmíněná pravděpodobnost

Pravděpodobnost jevu $A$ za předpokladu, že nastal jev $B$.

\[ \begin{align}
P(A|B) &= \frac{P(A \cap B)}{P(B)} 
\end{align} \]

## Nezávislé jevy

Jestliže jejich pravděpodobnosti na sobě nezávisí.

\[ \begin{align}
P(A) &= P(A|B) \\
P(B) &= P(B|A)
\end{align} \]

Jinak jsou jevy závislé.