---
layout: homepage
---

<!-- For LaTeX -->
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<script type="text/x-mathjax-config">
  MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    },
    options: {
      skipHtmlTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
      ignoreHtmlClass: 'tex2jax_ignore'
    }
  };
</script>

## About Me

Welcome to my website! I am a Ph.D. candidate at the [University of Maryland, College Park](https://www-math.umd.edu/), advised by [Yanir A. Rubinstein](https://math.umd.edu/~yanir/). I just finished my fifth year, and plan to graduate Spring 2025. I am interested in convex geometry and geometric analysis. My research includes: 

- 1 Book $2^n$
- 2

<!-- ## Research Interests

- **Computer Vision:** image recognition, image generation, video captioning
- **Machine Learning:** meta-learning, incremental learning, transfer learning -->


{% include_relative _includes/publications.md %}

## Code

[magicMahler](https://github.com/vmastr/magicMahler) is a Python library designed for geometric computations involving polytopes in the plane. Key features include calculating key essential notions from my reserach:
- Lp-Mahler volumes
- The isotropic constant
- The B-constant
- Implementation of the Mahler algorithm
- Implementation of th Graham scan for finding the extreme points in $nlogn$ time.

The library is currently under construction :)


<!-- 
{% include_relative _includes/services.md %} -->
