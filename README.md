# PheWAS

A fork of R PheWAS library, where I added codes for systolic pressure, diastolic pressure, and pulse rate.
```
install.packages("devtools")
#It may be necessary to install required as not all package dependencies are installed by devtools:
install.packages(c("dplyr","tidyr","ggplot2","MASS","meta","ggrepel","DT"))
devtools::install_github("vukadinovic936/PheWAS")
library(PheWAS)
```
Note that some versions of devtools do not install all dependencies, so one may need to install those using install.packages() first if there is an error.

You can additionally view the package help or vignette in R:
- `?PheWAS`
- `vignette("PheWAS-package")`
