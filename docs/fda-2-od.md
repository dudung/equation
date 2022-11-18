# finite difference approximation of second-order derivatives
It represents the second-order derivatives of a function $f(x)$ by its values at the discrete set of points in the form of

$$
\left[ \frac{d^2f(x)}{dx^2} \right]_i \approx \frac{1}{(\Delta x)^2} (f_{i+1} - 2f_i + f_{i-1}) + O(\Delta x)^2,
$$

where $f_i = f(x_i)$ and $x_{i+1} = x_i + \Delta x$.