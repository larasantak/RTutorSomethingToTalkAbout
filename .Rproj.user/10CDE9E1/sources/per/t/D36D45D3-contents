This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

This problem set is part of my bachelor's thesis at Ulm University. It is based on the paper **Something to Talk About: Social Spillovers in Movie Consumption**, which was published in the *Journal of Political Economy* in 2016. (https://www.journals.uchicago.edu/doi/abs/10.1086/688177)

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("larasantak/RTutorSomethingToTalkAbout", upgrade_dependencies=FALSE)
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorSomethingToTalkAbout)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorSomethingToTalkAbout")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorSomethingToTalkAbout",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
