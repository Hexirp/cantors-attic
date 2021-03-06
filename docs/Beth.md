---
title: The beth numbers, $\beth_\alpha$
permalink: Beth
redirect_from:
  - Beth_fixed_point
  - Beth_omega
  - Strong_limit
---

The *beth numbers* $\\beth\_\\alpha$ are defined by transfinite
recursion:

-   $\\beth\_0=\\aleph\_0$
-   $\\beth\_{\\alpha+1}=2^{\\beth\_\\alpha}$
-   $\\beth\_\\lambda=\\sup\_{\\alpha\\lt\\lambda}\\beth\_\\alpha$, for
    limit ordinals $\\lambda$

Thus, the beth numbers are the cardinalities arising from iterating the
power set operation. It follows by a simple recursive argument that
$\|V\_{\\omega+\\alpha}\|=\\beth\_\\alpha$.


## Beth one

The number $\\beth\_1$ is $2^{\\aleph\_0}$, the cardinality of the power
set $P(\\aleph\_0)$, which is the same as the
[continuum](Continuum "Continuum").
The
<a href="Continuum_hypothesis" class="mw-redirect" title="Continuum hypothesis">continuum hypothesis</a>
is equivalent to the assertion that $\\aleph\_1=\\beth\_1$. The
<a href="GCH" class="mw-redirect" title="GCH">generalized continuum hypothesis</a>
is equivalent to the assertion that $\\beth\_\\alpha=\\aleph\_\\alpha$
for all ordinals $\\alpha$.

  

## Beth omega

The cardinal $\\beth\_\\omega$ is the smallest uncountable cardinal
exhibiting the interesting property that whenever a set $X$ has
cardinality less than $\\beth\_\\omega$, then also the power set $P(X)$
also has size less than $\\beth\_\\omega$.

  

## Strong limit cardinal

More generally, a cardinal $\\kappa$ is a *strong limit cardinal* if
whenever $\\gamma\\lt\\kappa$, then $2^\\gamma\\lt\\kappa$. Thus, the
strong limit cardinals are those cardinals closed under the exponential
operation. The strong limit cardinals are precisely the cardinals of the
form $\\beth\_\\lambda$ for a limit ordinal $\\lambda$.

  

## Beth fixed point

A cardinal $\\kappa$ is a *$\\beth$-fixed point* when
$\\kappa=\\beth\_\\kappa$. Just as in the construction of
<a href="Aleph_fixed_point" class="mw-redirect" title="Aleph fixed point">aleph fixed points</a>,
we may similar construct beth fixed points: begin with any cardinal
$\\beta\_0$ and let $\\beta\_{n+1}=\\beth\_{\\beta\_n}$; it follows that
$\\kappa=\\sup\_n\\beta\_n$ is a $\\beth$-fixed point, since
$\\beth\_\\kappa=\\sup\_n\\beth\_{\\beta\_n}=\\sup\_n\\beta\_{n+1}=\\kappa$.
One may similarly construct $\\beth$-fixed points of any desired
cardinality, and indeed, the class of $\\beth$-fixed points are
precisely the closure points of the function
$\\alpha\\mapsto\\beth\_\\alpha$ and therefore form a closed unbounded
proper class of cardinals. Every $\\beth$-fixed point is an
$\\aleph$-fixed point as well. Since every model of ZFC satisfies the
existence of a $\\beth$-fixed point, it follows that no model of ZFC
satisfies $\\forall\\alpha &gt;0(\\beth\_\\alpha&gt;\\aleph\_\\alpha)$.


