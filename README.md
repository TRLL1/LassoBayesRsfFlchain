# LassoBayesRsfFlchain
In medical statistics, identifying the prognostic factors that have strong effects on the survival
times from the candidate variables is important. It is the foundation of building a parsimonious
model with good prediction accuracy. Many statisticians have proposed variable selection
methods for survival data, including statistical methods in the frequentist and Bayesian
framework. More recently, machine learning algorithms have been incorporated in model training
and prediction for survival analysis. This study is a comprehensive review of the Bayesian
variable selection, Cox-LASSO and Random Survival Forests for variable selection in survival
analysis. We have introduced the theories and computations of the 3 methods and applied them
to the in-built R data flchain with R-packages mombf, glmnet and rfsrc. We have interpreted
the results of these methods in feature selection on real-word data and compared the
characteristics of them, including the selection schemes, underlying models, assumptions and
some basic properties like scalability or model uncertainty. We are also aimed to answer the
open question left by the scholar that conducted the original study of flchain: does different
recruitment times cause difference in the sample? By stratification with respect to the sampling
year and analysis across different recruitment stages, we can finally give a positive answer to
the question from the perspective of variable selection. We hope that the study could provide
readers with a structured knowledge of the three methods and a reference when facing method
choices in real-life survival analysis.

The repository records the code to reproduce the application in this report.
