#options(repos = c(CRAN="https://cran.r-project.org"))
#options("repos" = c(CRAN = "http://cran.rstudio.com/"))
#
options(repos = c(CRAN="https://cran.r-project.org"))
#options(repos = c(CRAN="http://cran.r-project.org"))


options(prompt="> ")

.First <- function(){
#  if(interactive()){
#    library(utils)
#    timestamp(,prefix=paste("##------ [",getwd(),"] ",sep=""))
#  }
  cat("\nHola Bryn!\n")
  cowsay::say(praise::praise(), by = "random")
}


#.Last <- function(){
# cat("\nCiao! ", date(), "\n\n")
#}

options(blogdown.rmd = TRUE)
options(blogdown.author = 'Brian J. Knaus')
# options(blogdown.date = "`r format(Sys.time(), '%Y, %B, %d')`")
# options(blogdown.output = html_document:)
#    toc: true
#    code_folding: hide


# https://stackoverflow.com/a/4996252
# Suppress "Save workspace image? [y/n/c]:"
utils::assignInNamespace(
  "q", 
  function(save = "no", status = 0, runLast = TRUE) 
  {
    .Internal(quit(save, status, runLast))
  }, 
  "base"
)

