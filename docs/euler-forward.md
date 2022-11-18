# forward euler method
It computes value of a function $y(t + h)$ in the future from recent value $y(t)$ and its recent derifative $f[y(t), t]$ in the form of

$$
y_{n + 1} = y_n + h f(y_n, t_n) + O(h^2),
$$

with $y_n = y(t_n)$, $t_{n + 1} = t_n + h$, $f(y_n, t_n) = (dy/dt) |_{t = t_n}$, and $h$ is assumed to be constant for the sake of simplicity.
