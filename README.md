# SimpsonMethod
Simpson's method is a numerical method for approximating the definite 
integral of a function. It is a technique that uses quadratic interpolation
to estimate the area under the curve of a function.
The method works by dividing the area under the curve into a series of 
equal-width subintervals and approximating the area of each subinterval
with a quadratic function that passes through the endpoints of the interval 
and the midpoint. We keep dividing into subintervals until the desired degree
of accuracy has been obtained.  The sum of these approximations gives an estimate 
of the total area under the curve.
The formula for Simpson's method can be expressed as:
. ∫a b f(x)dx ≈ h/3 [f(a) + 4f(a+h) + f(b)]
where h is the width of each subinterval (h=(a+b)/2),
a is the lower limit of integration, b is the upper limit of integration, 
and f(x) is the function being integrated.
Simpson's method is a very accurate method of numerical integration.
In general, Simpson's rule is more accurate than the Composite Trapezoidal Rule, 
but it requires more function evaluations per interval. Newton-Cotes formulas, 
on the other hand, can be more accurate than either method, but they also require
more function evaluations.
