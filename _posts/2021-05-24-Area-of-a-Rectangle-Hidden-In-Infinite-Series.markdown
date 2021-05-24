---
layout: post
title:  "Deriving the Formula for the Area of a Rectangle from The Infinite Series Area of a Polygon Formula"
date:   2021-05-24 09:25:44 +0500
categories: math proof
---

$$\require{cancel}$$

Proof of extracting the Area Formula of Rectangles from Infinite Series Area Formula of Polygons:

The formula for the Area of a Rectangle is extracted from the formula for the Area of a Polygon using the following proof (from the book "A Complete guide to Mathamatics" by Ray Voice and Anna Voice):

Polygon-Area =  $$ \frac{1}{2} \sum_{i=0}^{n-1} (x_i y_{i+1} - x_{i+1} y_i) $$

> $$n = 4$$ because a Rectangle is a Polygon with 4 Verticies.

$$ n=4 \longrightarrow \frac{1}{2} [(x_0 y_{1} - x_{1} y_0) + (x_1 y_2 - x_2 y_1) + (x_2 y_3 - x_3 y_2) + (x_3 y_0 - x_0 y_3)] $$

> Since $$x_0 = 0$$ and $$y_0 = 0$$ because we are assuming the initial point is placed on origin

$$ \longrightarrow \frac{1}{2} [(\underline{x_0} y_{1} - x_{1} \underline{y_0}) + (x_1 y_2 - x_2 y_1) + (x_2 y_3 - x_3 y_2) + (x_3 \underline{y_0} - \underline{x_0} y_3)] $$

$$ \longrightarrow \frac{1}{2} [(\underline{0} y_{1} - x_{1} \underline{0}) + (x_1 y_2 - x_2 y_1) + (x_2 y_3 - x_3 y_2) + (x_3 \underline{0} - \underline{0} y_3)] $$

$$ \longrightarrow \frac{1}{2} [(\underline{0} - \underline{0}) + (x_1 y_2 - x_2 y_1) + (x_2 y_3 - x_3 y_2) + (\underline{0} - \underline{0})] $$

$$ \longrightarrow \frac{1}{2} [(x_1 y_2 - x_2 y_1) + (x_2 y_3 - x_3 y_2)] $$

> The *top-left* Vertex $$(x_1,y_1)$$ has $$x_1 = 0$$; and the *bottom-right* Vertex $$(x_3,y_3)$$ has $$y_3 = 0$$.

$$ \longrightarrow \frac{1}{2} [(\underline{x_1} y_2 - x_2 y_1) + (x_2 \underline{y_3} - x_3 y_2)] $$

$$ \longrightarrow \frac{1}{2} [(\underline{0} y_2 - x_2 y_1) + (x_2 \underline{0} - x_3 y_2)] $$

$$ \longrightarrow \frac{1}{2} [(- x_2 y_1) + (- x_3 y_2)] $$

> The *top-right* Vertex $$(x_2,y_2)$$ has the same width as the *bottom-right* Vertex $$(x_3,y_3)$$, hence $$x_2 = x_3$$; and similarly, the *top-right* Vertex $$(x_2,y_2)$$ has the same height as the *top-left* Vertex $$(x_1,y_1)$$, hence $$y_2 = y_1$$. Hence we'll assume $$x_2 = x_3 = a$$ and $$y_2 = y_1 = b$$.

$$ \longrightarrow \frac{1}{2} [(- \underline{x_2} \overline{y_1}) + (- \underline{x_3} \overline{y_2})] $$

$$ \longrightarrow \frac{1}{2} [(- \underline{a} \overline{b}) + (- \underline{a} \overline{b})] $$

$$ \longrightarrow \frac{1}{2} [(-ab) + (-ab)] $$

$$ \longrightarrow \frac{1}{2} [-ab -ab] $$

$$ \longrightarrow \frac{1}{2} [-2ab] $$

$$ \longrightarrow \frac{1}{\cancel{2}} [-\cancel{2}ab] $$

$$ \longrightarrow [-ab] $$

> Real Area in this instalce can only be Positive

$$ \text{Positive Area} \longrightarrow  ab $$

> We have already established that $$a$$ is the fartherest we go in the direction of *x-axis* so it is our Rectangle's width, and $$b$$ is the fartherest we go in the direction of *y-axis* so it is our Rectangle's height.

$$ \text{Polygon-Area} = ab $$

$$ \text{Rectangle-Area} = \text{Width x Height} $$

$$\text{Q.E.D} $$

> The Proof was written by Ray Voice as an original work and publication. It was published in the book "A Complete guide to Mathamatics" by Ray Voice and Anna Voice, comming soon to international markets.

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
