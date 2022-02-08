# Slides for IS 407

## Course Slide Decks

* [Week 1-01](https://uiuc-ischool-20221-jseo1005-1.github.io/slides/week1-01-welcome/week1-01-welcome.html).

* [Week 1-02](https://uiuc-ischool-20221-jseo1005-1.github.io/slides/week1-02-git+r/week1-02-git+r.html).

* [Week 2-01](https://uiuc-ischool-20221-jseo1005-1.github.io/slides/week2-01-data-viz).

* [Week 2-02](https://uiuc-ischool-20221-jseo1005-1.github.io/slides/week2-02-viz-num-cat).

* [Week 3-01](https://uiuc-ischool-20221-jseo1005-1.github.io/slides/week3-01-tidy+wrangle).

* [Week 3-02](https://uiuc-ischool-20221-jseo1005-1.github.io/slides/week3-02-df-join).

* [Week 4-01](https://uiuc-ischool-20221-jseo1005-1.github.io/slides/week4-01-tidying).



## Dev Toolkit Notes

Slides are built in using the **xaringan** package. See [here](https://github.com/yihui/xaringan) for more info on xaringan. There are two main reasons for choosing this format:

1. `xaringan` slides are R Markdown based, meaning code, output, and narrative can all live in one place and compiling the slides will run the R code as well.
2. Slide output is mobile friendly.

### Dev Instructions

Each slide deck is in its own folder, and one level above there is a custom css file. To compile the slides use `xaringan::inf_mr(cast_from = "..")`. This will launch the slides in the Viewer, and it will get updated as you edit and save your work.

## Acknowledgements

This course and materials are supported by and highly indebted to Mine Centinkaya-Rundel and RStudio Education Team.
