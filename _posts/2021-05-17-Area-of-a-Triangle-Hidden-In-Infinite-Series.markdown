---
layout: post
title:  "Deriving the Formula for the Area of a Triangle from The Infinite Series Area of a Polygon Formula"
date:   2021-05-17 05:57:44 +0500
categories: math proof
---

Proof of Triangle Area Formula extracted from Polygon Area Formula:

The formula for the Area of a Triange is extracted from the formula for the Area of a Polygon using the following proof (from the book "A Complete guide to Mathamatics" by Ray Voice and Anna Voice):

Polygon-Area =  $$ \frac{1}{2} \sum_{i=0}^{n-1} (x_i y_{i+1} - x_{i+1} y_i) $$

> n = 3 becaude Triangle is a Polygon with 3 Verticies.

$$ n=3 \longrightarrow \frac{1}{2} [(x_0 y_{1} - x_{1} y_0) + (x_1 y_2 - x_2 y_1) + (x_2 y_0 - x_0 y_2)] $$

> Since $$x_0 = 0$$ and $$y_0 = 0$$ because we are assuming the initial point is placed on origin

$$ \longrightarrow \frac{1}{2} [(\underline{x_0} y_{1} - x_{1} \underline{y_0}) + (x_1 y_2 - x_2 y_1) + (x_2 \underline{y_0} - \underline{x_0} y_2)] $$

$$ =  \frac{1}{2} [(\underline{0} y_{1} - x_{1} \underline{0}) + (x_1 y_2 - x_2 y_1) + (x_2 \underline{0} - \underline{0} y_2)] $$

$$ =  \frac{1}{2} [ (0 - 0) + (x_1 y_2 - x_2 y_1) + (0 - 0)] $$

$$ =  \frac{1}{2} [ (x_1 y_2 - x_2 y_1) ] $$


> $$y_2 = 0$$ since a second vertex of a Triangle can always be placed on either x-axis or y-axis if the first point is placed on origin.

$$ \longrightarrow \frac{1}{2} [ (x_1 \underline{y_2} - x_2 y_1) ] $$

$$ = \frac{1}{2} [ (x_1 \underline{0} - x_2 y_1) ] $$

$$ = \frac{1}{2} [ (0 - x_2 y_1) ] $$

$$ = \frac{1}{2} [- x_2 y_1 ] $$

$$ = \frac{- x_2 y_1}{2} $$

> Real Area in this instalce can only be Positive

$$ \text{Positive Area} \longrightarrow  \frac{x_2 y_1}{2} $$

> $$ x_2 $$ is the size of the Base, and $$ y_1 $$ is the size of the Height

$$ \text{Polygon-Area} = \frac{x_2 y_1}{2} $$

$$ \text{Triangle-Area} = \frac{\text{Height x Base}}{2} $$

$$\text{Q.E.D} $$

> The Proof was written by Ray Voice as an original work and publication. It was published in the book "A Complete guide to Mathamatics" by Ray Voice and Anna Voice, comming soon to international markets.

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
