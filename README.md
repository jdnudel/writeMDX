
<!-- README.md is generated from README.Rmd. Please edit that file -->

# writeMDX :japanese\_ogre:

`writeMDX` writes Rmarkdown (`.Rmd`) files to
[MDX](https://github.com/mdx-js/mdx). Nice and simple :sunglasses:

## Install :open\_hands:

You can install it with
`remotes::install_github("RobertMyles/writeMDX")`.

## Use :point\_down:

With a file named “heyho.Rmd”:

``` r
writeMDX("heyho.Rmd")
```

If you’d like to use it from the command line, first run
`writeMDX::cli()`. Then it’s just:

``` bash
writeMDX "heyho.Rmd"
```

## Why?? :confused:

I love [React](https://reactjs.org/), and I just rebuilt my
[website](https://www.robertmylesmcdonnell.com/) using
[gatsby.js](https://www.gatsbyjs.org/), so now I want all the ease and
power of MDX. The only missing piece of the puzzle was doing some stuff
in R, and then writing it out to an `.mdx` file that I can use to add in
all the other stuff I want, like D3 graphs. R + React + Markdown =
:purple\_heart:

## No CRAN? :cry:

This won’t go on CRAN, since it’s mainly [rmarkdown
package](https://rmarkdown.rstudio.com/) functions with an added format,
which you can do yourself [quite
easily](https://bookdown.org/yihui/rmarkdown/format-custom.html).
