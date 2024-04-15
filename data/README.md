data
====

# Basic info

Your data files (.csv) will live here. 
When you have finished segmenting and have executed all your scripts you 
should have 6 .csv files here. 

```{R}

library(tidyverse)
library(readr)



bi01 <- read_csv("pa_4/data/bi01.csv")
View(bi01)
bi02 <- read_csv("pa_4/data/bi02.csv")
View(bi02)
bi03 <- read_csv("pa_4/data/bi03.csv")
View(bi03)
ne01 <- read_csv("pa_4/data/ne01.csv")
View(ne01)
ne02 <- read_csv("pa_4/data/ne02.csv")
View(ne02)
ne03 <- read_csv("pa_4/data/ne03.csv")
View(ne03)








