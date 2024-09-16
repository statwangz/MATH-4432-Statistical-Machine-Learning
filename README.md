# Tutorials for MATH 4432 Statistical Machine Learning

<!-- metrics -->
<p align="center">
 <a href="https://hits.seeyoufarm.com">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fstatwangz%2FMATH-4432-Statistical-Machine-Learning&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/>
 </a>
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
 <a href="https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning/issues?q=is%3Aissue+is%3Aclosed">
  <img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/statwangz/MATH-4432-Statistical-Machine-Learning">
 </a>
</p>

## Course Information

[MATH 4432 Statistical Machine Learning](https://sites.google.com/site/eeyangc/teaching/math-4432-statistical-machine-learning)
 
Instructor: Prof. Can Yang

Teaching Assistant: Zhiwei Wang (<zhiwei.wang@connect.ust.hk>)

This course is open to senior undergraduates in applied mathematics, statistics, and engineering who are interested in learning from data.
It covers hot topics in statistical learning, also known as machine learning, featured with various applications.

## Tutorial Files

- T01, T02, T04, T05

The source files of the slides are `.Rmd` files.
If you are interested in how to create slides through R Markdown, you can have a look at them.

To get a full view of the slides, I recommend you open the `.html` files (e.g., [`Introduction.html`](https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning/blob/main/T01%20A%20Brief%20Introduction%20to%20R/Introduction.html)) with your browser after downloading the entire repository.
Typically this works best in Chrome.

I also provide the PDF version via John Paul Helveston and Garrick Aden-Buie's R package [**renderthis**](https://github.com/jhelvy/renderthis).
```r
renderthis::to_pdf(from = "filename.Rmd", complex_slides = TRUE, partial_slides = FALSE)
```
**However, the “complex” slides containing panelsets or other HTML widgets / advanced features might not render well as a PDF.**

- The others are `.ipynb` files. 

## Reference

- [An Introduction to Statistical Learning: With Applications in R](https://www.statlearning.com/). Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani.

## Acknowledgments

- The tutorial notes are modified and supplemented based on the materials from my "elder academic brother" (大师兄), Prof. Mingxuan Cai, CityU (miss him every day 😭).
 
- Slides created via Yihui Xie's R package [**xaringan**](https://github.com/yihui/xaringan).

- Theme customized via Garrick Aden-Buie's R package [**xaringanthemer**](https://github.com/gadenbuie/xaringanthemer).

- Tabbed panels created via Garrick Aden-Buie's R package [**xaringanExtra**](https://github.com/gadenbuie/xaringanExtra/).
