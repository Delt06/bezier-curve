# Bezier Curve

- Quadratic
- Cubic
- General Form

Also, a component with a custom editor are available.

## Code example

```c#
// from
var p0 = Vector3.zero;
// intermediate point
var p1 = Vector3.up;
// to
var p2 = Vector3.one;
// take the point at 25%
var pointOnCurve = BeizerCurve.Quadratic(p0, p1, p2, 0.25f);
```