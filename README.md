# tufte-css-latex
Edward Tufte uses a distinctive style in his handouts: simple, with well-set typography, extensive sidenotes, and tight integration of graphics and charts. Liepmann's [tufte-css](https://github.com/edwardtufte/tufte-css) brings that style to HTML documents. This project, `tufte-css-latex`, aims to make it so we can develop text in Latex and get nice PDF output for hardcopy, but also use tufte.css with tools like [`tex4ht`](https://tug.org/tex4ht/) and [`tex4ebook`](https://github.com/michal-h21/tex4ebook) to turn it into reflowable epub/epub3/ibook for use on devices. 

This project is directly inspired by and based on [Tufte-LaTeX](https://tufte-latex.github.io/tufte-latex/), the [R Markdown Tufte Handout](http://rmarkdown.rstudio.com/examples/tufte-handout.pdf), and [tufte-css](https://github.com/edwardtufte/tufte-css).

## From Tufte CSS, and getting started
Tufte CSS provides a live version at <https://edwardtufte.github.io/tufte-css/> which is the best overview of the project. In normal usage of Tufte CSS, just copy `tufte.css` and the `et-book` font directory to your project and add the following to your HTML doc's head block:
```html
<link rel="stylesheet" href="tufte.css"/>
```

Here we provide Latex package definitions and tex4ht config (cfg) files so that equivalent output can be generated from Latex. 

## Contributors
* Dennis Evangelista
  
## Thanks to:
* Edward Tufte, Dave Liepmann, and team
