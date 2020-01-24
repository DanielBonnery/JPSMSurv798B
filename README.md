#R data and demo package for the JPSM lectures surv798B (Small area estimation).

A first package was used to teach small area at JPSM.
Then a new package was created (see <github.com/DanielBonnery/SaeComputations>) to be used in short courses on Small area. The installation of JPSMsurv798B is equivalent to the installation of SaeComputations. 

##Installation
execute in R:
```{R}
install.packages("devtools)"
devtools::install_github("DanielBonnery/JPSMsurv798B")
```

##Use
```{R}
library(SaeComputations)
demo(ADM)
demo(EB)
demo(EB2)
demo(MCMC)
```
