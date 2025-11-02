+++
title = "Lines and Circles"
description = "Intersections between lines and circles in high school mathematics"
slug = "line-and-circle"
date = 2024-05-01T01:00:00Z
tags = ["geometry", "high school math"]
categories = ["mathematics"]
translationKey = "line-and-circle"
+++

> "In the plane, the meeting of a line and a circle hides every secret of analytic geometry."

## Key ideas

A circle in the plane can be written in standard form \((x-a)^2 + (y-b)^2 = r^2\), where \((a,b)\) is the center and \(r\) is the radius. A line is often described by the slope-intercept form \(y = mx + c\) or the general form \(Ax + By + C = 0\).

To determine how a line and a circle are positioned, substitute the line equation into the circle equation to obtain a quadratic equation in one variable:

\[
  (1 + m^2)x^2 + 2(m(c-b) - a)x + (a^2 + (c-b)^2 - r^2) = 0.
\]

- Discriminant \(\Delta > 0\): two intersections (the line and circle cross).
- Discriminant \(\Delta = 0\): one intersection (the line is tangent).
- Discriminant \(\Delta < 0\): no intersection (the line misses the circle).

The same logic applies when the line is written in general form: plug it into the circle and inspect the discriminant of the resulting quadratic.

## Distance to the center

For a line in general form, the distance from the center to the line is

\[
  d = \frac{|Aa + Bb + C|}{\sqrt{A^2 + B^2}}.
\]

Compare \(d\) with the radius \(r\):

- If \(d < r\), the line intersects the circle.
- If \(d = r\), the line is tangent to the circle.
- If \(d > r\), the line stays outside the circle.

## Example: finding intersection points

Consider the circle \((x-1)^2 + (y+2)^2 = 25\) and the line \(3x - 4y - 20 = 0\).

1. Compute the distance: \(d = |3 \cdot 1 - 4 \cdot (-2) - 20| / 5 = 3\). Since \(r = 5\), the line crosses the circle.
2. Rewrite the line as \(y = \frac{3x-20}{4}\) and substitute into the circle:

\[
  (x-1)^2 + \left(\frac{3x-20}{4} + 2\right)^2 = 25.
\]

3. Simplify to obtain \(25x^2 - 170x + 289 = 0\), which yields \(x = 4\) or \(\frac{289}{25}\).
4. Substitute back into the line to find \(y\); the intersection points are \((4, -2)\) and \((\frac{289}{25}, -\frac{47}{25})\).

## Practice prompts

- Combine the line \(y = x + 1\) with the circle \(x^2 + y^2 = 10\). Decide their relative position and find the intersection points.
- Construct a line through \((2,3)\) that is tangent to the circle \((x-3)^2 + (y-1)^2 = 13\).
- Investigate the number of intersections between the vertical line \(x = k\) and the unit circle \(x^2 + y^2 = 1\); describe the conditions on the parameter \(k\).

