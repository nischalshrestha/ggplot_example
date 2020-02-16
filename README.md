# ggplot_example

Example of ggplot tasks using the `learnr` package for user study experiments. 

The `learnr` package allows one to write in RMarkdown and run the document as an interactive Shiny app, allowing code execution. This is nifty for design of programming tasks such as plots.

# Run
You have two options:
1) Locally on the computer via RStudio 'Run Document' command on the [ggplot.Rmd](https://github.com/nischalshrestha/ggplot_example/blob/master/ggplot/ggplot.Rmd) file, or
2) You can publish the app on a server like shinyserver.io: https://nshrest.shinyapps.io/ggplot_tasks/ (or your own server)

The first option is the least riskiest as it doesn't rely on shinyservers being stable etc.

# Dependencies:

You need RStudio (v1.0.136 or later) and the following R packages:

- ggplot2 (to plot)
- knitr (to run the Rmd file)
- shiny (to allow shiny prerendered app for learnr)
- learnr (to run the interactive tutorial format)
- rvest (to parse html output for logging warnings)
- gradethis (to check code for correctness---currently not being used)

All of these can be installed via `install.packages(...)` command. 
