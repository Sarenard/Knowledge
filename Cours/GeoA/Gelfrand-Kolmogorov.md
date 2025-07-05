---
type: Théorème
---

# Gelfrand-Kolmogorov (1939)

On associe à chaque espace topologique $X$ la $\mathbb R$-algèbre $C(X) = C^0(X, \mathbb R)$. Alors, tout point $x \in X$ donne naissance à un idéal $m_x = \{f \in C(X) \quad f(x) = 0\}$, qui est maximal (car $C(X)/m_x \ \cong R$)

On note $Spm(C(X))$ l'ensemble des idéaux maximaux en question, appelé spectre maximal de C(X). On peut le munir de la topologie engendrée par les 
$$D(f) = \{m \in Spm(C(X)) \quad f \not \in m\}$$

> **Théorème.**
> Si $X$ est compact, l'application
> $$\begin{align*}
  \phi \colon X &\to Spm(C(X))\\
  x &\mapsto m_x.
\end{align*}$$
> est un homéomorphisme
> > **Preuve.**
> > TODO

Alors, chaque application continue $f : X \to Y$ entre espaces compacts induit un morphisme de $\mathbb R$-algèbres
$$\begin{align*}
  f^* \colon C(Y) &\to C(X)\\
  \phi &\mapsto \phi \circ f.
\end{align*}$$
Et donc C est un foncteur contravariant.

> **Théorème.**
> Le foncteur C, de la catégorie des espaces topologiques compacts dans la catégorie des $\mathbb R$-algèbres (commutatives et unitaires) est pleinement fidèle

En gros, il est possible de retrouver $X$ en connaissant $C(X)$.

> **Théorème.**  
> Si $X$ est un sous-ensemble algébrique de $\mathbb A_k^n$, alors
> $$\begin{align*}
  f \colon X &\to Spm(\Gamma(X))\\
  x &\mapsto I(\{x\}).
\end{align*}$$
> est une bijection

En fait, en munissant $Spm(\Gamma(X))$ de la topologie engendrée par les $D(f) = \{m \quad f \not \in m\}$, la bijection du dessus est un homéomorphisme.

Il est donc possible de retrouver $X$ en connaissant $\Gamma(X)$.
