# Usefuel Stats

## 📖 **About**

This repository was initiated by [SST](https://github.com/sarahsmithtripp) to share easy-to-use resources for applying various statistical analysis methods and techniques. We have included resources that provide a good introduction to data analysis that may be more readable than the traditional statistics textbooks.

All the resources include code written in `R`.<br>. We organize this repository by datatype and assumption not met. 

| Data type                                      | Assumption                          | Modelling approach                                                                                                                                            |  
|------------------------------------------------|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Time series                                    |                                    | [change point detection](https://www.marinedatascience.co/blog/2019/09/28/comparison-of-change-point-detection-methods/#linear-relationship-zx-with-1-break)   |
| Time series                                    |                                    | [Looking at time series ](https://lindeloev.github.io/mcp/articles/packages.html)                                                                              |
| Continuos variable~difference between groups   |                                    | [ANOVA](https://ourcodingclub.github.io/tutorials/anova/)                                                                                                      |
| Continuos variable~difference between groups   | non-independent observations       | [Mixed ANOVA](https://www.datanovia.com/en/lessons/mixed-anova-in-r/ )                                                                                         |
| Continuos variable~ continuos or catagorical covariables | non-independent observations       | [Introduction to linear mixed models](https://ourcodingclub.github.io/tutorials/mixed-models/)                                                       |
| Continuos variable~ continuos or catagorical covariables | non-independent observations       | [Mixed linear models definitions](https://bookdown.org/steve_midway/DAR/random-effects.html)                                                      |
| Continuos variable~ continuos or catagorical covariables | non-independent observations       | [Fitting mixed linear models ](https://cran.r-project.org/web/packages/lme4/vignettes/lmer.pdf)                                                      |
| Binary data/ Count data                                  |   non-normal distribution          | [Generalized linear models -GLM](https://bbolker.github.io/goettingen_2019/notes/glm_basic.html)                                                     |
| Binary data/ Count data                                  |   non-normal distribution          | [Confidence Intervals for GLMs ](https://fromthebottomoftheheap.net/2018/12/10/confidence-intervals-for-glms/)                                       |
| Binary data/ Count data                                  |   zero inflated                    | [Zero inflated models ](https://cran.r-project.org/web/packages/glmmTMB/vignettes/glmmTMB.pdf)                                                       |
| Binary data/ Count data                                  |   zero inflated                    | [Hurdle models](https://m-clark.github.io/models-by-example/hurdle.html)                                                                                   |
| Binary data/ Count data                                  |   zero inflated                    | [Visualizing zero inflated models ](https://cran.r-project.org/web/packages/glmmTMB/vignettes/model_evaluation.pdf)                                  |
| Continuos / Binary data/ Count data                      |   non-linear relationships         | [Generalized Additive Models-GAMs](https://noamross.github.io/gams-in-r-course/chapter2)                                                             |
| Bounded data / proportions                               |                                    | [Beta regression models](https://www.andrewheiss.com/blog/2021/11/08/beta-regression-guide/#a-beta-regression)                                       |
| Bounded data / proportions                               |  zero inflated              | [Zero inflated beta regression](https://cran.r-project.org/web/packages/DHARMa/vignettes/DHARMa.html))                                                      |
| test models assuptions and plot residuals                |                              | [DHARMa: residual diagnostics](https://stats.stackexchange.com/questions/309047/zero-inflated-beta-regression-using-gamlss-for-vegetation-cover-data)      |
| test models assuptions and plot residuals                |                              | [DHARMa for unsupported models](https://aosmith.rbind.io/2017/12/21/using-dharma-for-residual-checks-of-unsupported-models/)                               |
