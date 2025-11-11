---
site: sandpaper::sandpaper_site
---

The best way to learn how to program is to do something useful, so this introduction to R is built around a common scientific task: data analysis.
I've focused on best practices for R programming to start, included some use of {knitr}, RMarkdown and Quarto and finish building R packages.

My real goal isn't to teach you how to use R, but to teach you the basic concepts that all programming depends on.

:::::::::::::::::::::::::::::::::::::::::: prereq

Learners need to understand the concepts of files and directories (including the working directory).
I will use RStudio to teach this lesson, but it is not required.
In fact, I put this lesson together using Neovim.

## Software Setup

This lesson assumes you have R and RStudio installed on your computer.

[Download and install the latest version of R](https://www.r-project.org/) for your computer.
[Download and install RStudio](https://www.rstudio.com/products/rstudio/download/#download).
RStudio is an application (an integrated development environment or IDE) that facilitates the use of R and offers a number of nice additional features.
You will need the free desktop version for your computer.

You will also need the following R packages installed on your computer:

```r
install.packages(c("devtools", "tidyverse", "here", "roxygen2", "knitr", "desc"))
```

::::::::::::::::::::::::::::::::::::::::::::::::::
