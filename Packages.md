
# Installing packages

Packages are publicly available collections of functions that have been written by users and developers for specific tasks. THe R version you downloaded comes with a basic collection of functions but the strength of R is the large number of packages contributed by the R community,

Most of the packages are available through CRAN and can be installed as follows:

```{r}
#install Liam Revell's "phytools" package
install.packages("phytools")

#to install several pacakges at once, do the following
install.packages(c("phytools", "ape", "geiger", "OUwie"))
```

To use the functions contained within a package, you need to tell R to load the library

```
#load the phytools package
library(phytools)
```
