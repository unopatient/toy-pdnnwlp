pdnnwlp

Before we start aything we need to obtain the global Lipschitz constant for the DNN architecture.

We need this constant $L$ so that we can solve for $\gamma$ in $\epsilon = 2 \gamma L$.

We need this for the dsicretization of $x$, $y$, and $\phi$ via approximation as a sum of inverse powers of 2.

EX:

$$
\phi_{i} = -1 + 2\sum_{h=1}{N_{\gamma}}2^{-h}z_{(i,h)^{\phi}}, i\in\[N\]
$$