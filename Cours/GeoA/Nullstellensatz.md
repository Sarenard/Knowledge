---
type: Théorème
---

# Nullstellensatz (1893)

Plaçons-nous dans l'espace affine $\mathbb A_k^n = k^n$

> **Définition.**  
> On appelle sous ensemble algébrique de l'espace affine un ensemble de la forme
> $$V(I) = \{x \in k^n \quad |\quad f(x) = 0 \quad  \forall x \in I\}$$

Avec $I$ un idéal de la $k$-algèbre de polynomes $k[t_1, \dots, t_n]$, qui représente les fonctions polynomiales sur $\mathbb A_k^n$.

Un tel ensemble est muni de la topologie de Zariski, dont les fermés sont les sous ensembles algébriques inclus dans $V$.

Réciproquement, à toute partie $V \subset A^n_k$ on associe l'idéal
$$I(V) = \{f\in k[t_1, \dots, t_n] \quad f_{|V} = 0\}$$
(on confondra polynome et fonction polynomiale associée)

> **Définition.**  
> $\Gamma(V) = k[t_1, \dots, t_n] / I(V)$ est l'algèbre des fonctions régulières sur $V$

> **Théorème.**  
> Soit $k$ un corps algébriquement clos. Pour tout idéal $I \subset k[t_1, \dots, t_n]$ on a
> $$I(V(I)) = \sqrt{I}$$
> Ainsi, les applications $I \mapsto V(I)$ et $V \mapsto I(V)$ induisent une bijection décroissante entre l'ensemble des sous ensembles algébriques de $\mathbb A_k^n$ et l'ensemble des idéaux radicaux de $k[t_1, \dots, t_n]$.

En fait, le Nullstellensatz entraine que les idéaux maximaux sont tous de la forme
$$I = (t_1-a_1, \dots, t_n-a_n)$$
