# Statistics
library(readxl)
> datafile <- read_excel("C:/Users/YOGA SREE/OneDrive/Desktop/datafile.xls")
> View(datafile)
> mean(datafile$`Number (in Million)`)
[1] 33.23471
> var(datafile$`Gross Output (Crore)`)
[1] 4.44567e+11
> mean(datafile$`Gross Output (Crore)`)
[1] 1191018
> sd(datafile$`Number (in Million)`)
[1] 17.55231
