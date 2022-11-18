# finite difference approximation of first-order derivatives
It represents the first-order derivatives of a function $f(x)$ by its values at the discrete set of points in the form of

$$
\left[ \frac{df(x)}{dx} \right]_i \approx \frac{1}{\Delta x} (f_{i+1} - f_i) + O(\Delta x),
$$

$$
\left[ \frac{df(x)}{dx} \right]_i \approx \frac{1}{2\Delta x} (f_{i+1} - f_{i-1}) + O(\Delta x)^2,
$$

$$
\left[ \frac{df(x)}{dx} \right]_i \approx, \frac{1}{\Delta x} (f_i - f_{i-1}) + O(\Delta x),
$$

which are known as forward, central, and backward differences, respectively, where $f_i = f(x_i)$ and $x_{i+1} = x_i + \Delta x$.