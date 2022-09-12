# Tutorial notes

## Course information

MATH 4432 Statistical Machine Learning

Homepage: https://sites.google.com/site/eeyangc/teaching/math-4432-statistical-machine-learning
 
Instructor: Prof. YANG Can, HKUST

This course is open to senior undergraduates in applied mathematics, statistics, and engineering who are interested in learning from data.
It covers hot topics in statistical learning, also known as machine learning, featured with various applications.

## Tutorial files

The source files of the slides are `.rmd` files.
If you are interested in how to create slides through R Markdown, you can have a look at them.

To get a full view of the tutorial notes, I recommend you open the `.html` files (e.g., [`Introduction.html`](https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning/blob/main/T01%20A%20brief%20introduction%20to%20R/Introduction.html)) with your browser after downloading the entire repository.
Don't forget to download `xaringan-themer.css` to get the customized **HKUST** theme.
Typically this works best in Chrome.

I also provide the pdf version via John Paul Helveston and Garrick Aden-Buie's R package [**renderthis**](https://github.com/jhelvy/renderthis)
```r
renderthis::to_pdf(from = "filename.Rmd", complex_slides = TRUE, partial_slides = FALSE)
```
However, the “complex” slides containing panelsets or other HTML widgets / advanced features might not render well as a PDF perfectly.

## Reference

- [An introduction to statistical learning](https://www.statlearning.com/). Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani.

## Acknowledgments
 
- Slides created via Yihui Xie's R package [**xaringan**](https://github.com/yihui/xaringan).

- Theme customized via Garrick Aden-Buie's R package [**xaringanthemer**](https://github.com/gadenbuie/xaringanthemer).

- Tabbed panels created via Garrick Aden-Buie's R package [**xaringanExtra**](https://github.com/gadenbuie/xaringanExtra/).
