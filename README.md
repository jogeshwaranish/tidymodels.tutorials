
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Tutorials for *Tidy Modeling with R*

<!-- badges: start -->

[![R-CMD-check](https://github.com/PPBDS/tidymodels.tutorials/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/PPBDS/tidymodels.tutorials/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

## About this package

**tidymodel.tutorials** provides tutorials for [*Tidy Modeling with
R*](https://www.tmwr.org/) by Max Kuhn and Julia Silge. These tutorials
assume that you have some experience working with the tools provided by
the **[tutorial.helpers](https://ppbds.github.io/tutorial.helpers/)**
package. As long as you have completed the “Getting Started” tutorial
from that package, you should be fine.

The main audience for these tutorials is instructors teaching data
science and their students. Instructors want students to, for example,
read Chapter 8 of [*Tidy Modeling with R*](https://www.tmwr.org/) (or
something similar), typing in the code at the R Console along the way.
Sadly, students almost never do that. Indeed, many (most?) of them won’t
even read the assigned chapter.

The promise we make to instructors is that, if they assign our tutorial
for Chapter 8, then students will type in at least 90% of the code
examples from the chapter, and then run the code to see what happens. We
also pull out some of the most important prose from the chapter and do
everything we can to cajole/trick students into reading it. These
[two](https://ppbds.github.io/tutorial.helpers/articles/instructions.html)
[essays](https://ppbds.github.io/tutorial.helpers/articles/books.html)
provide background information about our approach.

Our causal claim is that, if an instructor were to randomly assign half
the class to do these tutorials and half to simply complete the reading,
the half completing the tutorials would perform much better for the rest
of the course.

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
remotes::install_github("PPBDS/tidymodels.tutorials")
```

If R offers you the option to update some packages, you should do so.
For packages that need compilation, feel free to answer “no”.

Then **restart your R session** or **restart RStudio**.

## Accessing tutorials

In order to access the tutorials, start by loading the package.

``` r
library(tidymodels.tutorials)
```

You can access the tutorials via the Tutorial tab in the top right
(Environment) pane in RStudio.

If either of the following is happening to you

<ul>
<li>
Cannot find the Tutorial pane
</li>
<li>
Cannot find any tidymodels tutorials
</li>
</ul>

Then **remember to restart your R session** after installing the
package.

Because tutorials within the Tutorial pane are sorted in alphabetical
order by the name of the package, the **tidymodels.tutorials** will be
toward the bottom. If you don’t see any tutorials, try clicking the
“Home” button – the little house symbol with the thin red roof in the
upper right.

In order to expand the window, you can drag and enlarge the tutorial
pane inside RStudio. In order to open a pop-up window, click the “Show
in New Window” icon next to the home icon.

You may notice that the Jobs tab in the lower left will create output as
the tutorial is starting up. This is because RStudio is running the code
to create the tutorial. If you accidentally clicked “Start Tutorial” and
would like to stop the job from running, you can click the back arrow in
the Jobs tab, and then press the red stop sign icon. Your work will be
saved between RStudio sessions, meaning that you can complete a tutorial
in multiple sittings. Once you have completed a tutorial, follow the
instructions on the tutorial `Submit` page and, if you’re a student,
submit your answers as instructed.
