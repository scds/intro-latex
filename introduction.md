---
layout: default
title: Introduction
nav_order: 3
---

<!-- Allows LaTeX-like Math -->
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
    skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
    inlineMath: [['$','$']],
    displayAlign: 'center',
    }
});
</script>

<script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']]
  },
  chtml: {
    scale: 1
  }
};
</script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js">
</script>

# Workshop Introduction

<!-- Follow along with the introductory video, slides, or text below.

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/eda1d592-eb4e-453d-bd23-0e1a84800ee0/public?autoplay=false&automute=false"></iframe>
[View original here.](https://echo360.ca/media/eda1d592-eb4e-453d-bd23-0e1a84800ee0/public) -->

## What is LaTeX?

LaTeX is a markup language for creating high-quality documents. As a markup language, LaTeX takes care of the document formatting so that you can focus on content. Unlike Microsoft Word and Google Docs, you don't need to worry about the formatting of content after the initial setup.

LaTeX is also a very popular tool used to typeset mathematics and other special symbols.

## What Can You Create With LaTeX?

LaTeX is used to make a variety of different types of documents, some of which include:
- Articles
- Book Chapters
- Theses and Dissertations
- Presentations
- Posters
- Assignments and Problem Sets
- Resumes and CVs

## Examples of Math Typesetting in LaTeX    

Using LaTeX for mathematics is a lot quicker than other means of writing. It automatically takes care of the sizing of symbols and the spacing between characters. Below are a couple examples of equations, written both independent of text but also in-line with text.

<div class="code-example">

$$ax^2 + bx + c = 0$$


$$ \sum_{n=1}^{\infty} \frac{1}{n} = 1 + \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \ldots $$


$$ f(x) = \int_{a}^{b}K(x,t)\phi(t)dt $$


The universal law of gravitation can be expressed with the equation $ F = \frac{Gm_{1}m_{2}}{r^{2}} $.

</div>

## Examples of Figures with LaTeX and tikz

<div style="display: flex" class="code-example">

<img width="40%" src="assets/img/introduction/tikz1.svg">

<img width="40%" src="assets/img/introduction/tikz2.svg">

</div>