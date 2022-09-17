# Tutorials for MATH 4432 Statistical Machine Learning

<!-- metrics -->
<p align="center">
 <a href="https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning/stargazers">
  <img alt="GitHub stars" src="https://img.shields.io/github/stars/statwangz/MATH-4432-Statistical-Machine-Learning">
 </a>
 <a href="https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning/network">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/statwangz/MATH-4432-Statistical-Machine-Learning">
 </a>
 <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/statwangz/MATH-4432-Statistical-Machine-Learning">
 <a href="https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning/issues">
  <img alt="GitHub issues" src="https://img.shields.io/github/issues/statwangz/MATH-4432-Statistical-Machine-Learning">
 </a>
</p>

## Course information

[MATH 4432 Statistical Machine Learning](https://sites.google.com/site/eeyangc/teaching/math-4432-statistical-machine-learning)
 
Instructor: Prof. YANG Can

Teaching assistant: WANG Zhiwei (<zhiwei.wang@connect.ust.hk>)

This course is open to senior undergraduates in applied mathematics, statistics, and engineering who are interested in learning from data.
It covers hot topics in statistical learning, also known as machine learning, featured with various applications.

## Tutorial files

The source files of the slides are `.Rmd` files.
If you are interested in how to create slides through R Markdown, you can have a look at them.

To get a full view of the slides, I recommend you open the `.html` files (e.g., [`Introduction.html`](https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning/blob/main/T01%20A%20brief%20introduction%20to%20R/Introduction.html)) with your browser after downloading the entire repository.
Typically this works best in Chrome.

I also provide the PDF version via John Paul Helveston and Garrick Aden-Buie's R package [**renderthis**](https://github.com/jhelvy/renderthis).
```r
renderthis::to_pdf(from = "filename.Rmd", complex_slides = TRUE, partial_slides = FALSE)
```
However, the “complex” slides containing panelsets or other HTML widgets / advanced features might not render well as a PDF.

## Reference

- [An Introduction to Statistical Learning: With Applications in R](https://www.statlearning.com/). Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani.

## Acknowledgments

- The tutorial notes are modified and supplemented based on the materials from my "big academic brother" (大师兄), Prof. CAI Mingxuan, CityU.
 
- Slides created via Yihui Xie's R package [**xaringan**](https://github.com/yihui/xaringan).

- Theme customized via Garrick Aden-Buie's R package [**xaringanthemer**](https://github.com/gadenbuie/xaringanthemer).

- Tabbed panels created via Garrick Aden-Buie's R package [**xaringanExtra**](https://github.com/gadenbuie/xaringanExtra/).
