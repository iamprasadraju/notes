---
title: "Line Equation"
date: 2026-03-28
tags: []
---

## What is a Line ?

A straight one-dimensional figure that extends infinitely in both directions and has no thickness or endpoints.

- It is made up of infinitely many points
- It has length but no width
- It continues forever in both directions

<center><img width="50%"
src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Adcinak.svg/3840px-Adcinak.svg.png" alt="line"></center>

## What is an equation ?

An equation is written as two expressions, connected by an equals sign ("=").The expressions on the two sides of the equals sign are called the "left-hand side" and "right-hand side" of the equation.


## What is line equation ?

A linear equation represents a straight line and has variables raised only to the power of 1, with no products of variables or higher powers. For example, in two variables, it takes the form $Ax+By+C=0$, where A, B, and C are constants. When graphed, its solutions form a straight line.

<u>Common Forms:</u> 

**0. General Form:** $Ax + By + C = 0$

* (A, B, C) are constants, with (A) and (B) not both zero

**1. Slope–Intercept Form:** $y = mx + c$

* m: slope (gradient)
* c: $y$-intercept (where the line crosses the $y$-axis)

**2. Point–Slope Form:** $y - y_1 = m(x - x_1)$

* Used when the slope $m$ and one point $(x_1, y_1)$ are known

**3. Two–Point Form:** $\frac{y - y_1}{x - x_1} = \frac{y_2 - y_1}{x_2 - x_1}$

* Used when two points $x_1, y_1$ and $x_2, y_2$ are known

**4. Intercept Form:** $\frac{x}{a} + \frac{y}{b} = 1$

* $a$: $x$-intercept
* $b$: $y$-intercept
---
### WTF: What are these equations, and where do they come from?

RAW thinking: 

- <span style="background-color: yellow">To draw a line, we need either two points or one point and the slope. Without this information, we cannot draw a line.</span>
- <span style="background-color: yellow">Why? Because infinitely many lines can pass through a single point. To define a unique line, we need either another point (to determine the slope) or the slope itself. If the slope is given along with a point, there is only one line with that exact slope passing through the point.</span>

**Deriviation from raw thinking:**

**slope:** The slope or gradient of a line is a number that describes the direction of the line on a plane. Often denoted by the letter m, slope is calculated as the ratio of the vertical change to the horizontal change ("rise over run") between two distinct points on the line, giving the same A slope is the ratio of the vertical distance (rise) to the horizontal distance (run) between two points.


$$
m = \frac{\Delta y}{\Delta x} = \tan(\theta)
$$


<center>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Wiki_slope_in_2d.svg/1280px-Wiki_slope_in_2d.svg.png" width="40%", height = "40%"></center>

From this: 

$$ m = \frac {y - y_1} {x - x1} $$

$$ (y - y_1) = m(x - x_1)$$


If two points are known, then the slope is constant for a straight line:

$$
\frac{y - y_1}{x - x_1} = \frac{y_2 - y_1}{x_2 - x_1}
$$

**slope-intercept form**

Start with the definition of slope between a general point $(x, y)$ 
and the y-intercept $(0, c)$:

$$
m = \frac{y - c}{x - 0}
$$

$$
m = \frac{y - c}{x}
$$

Multiply both sides by $x$:

$$
mx = y - c
$$

Rearrange:

$$
y = mx + c
$$
