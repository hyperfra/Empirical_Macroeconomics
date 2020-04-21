# Empirical Macroeconomics: the identification of shocks
This course provides a non-systematic account of a range of research methods in empirical macroeconomics to identify shocks. It is intended as an apprenticeship to students interested in working in research departments. Students will reproduce the results of three published paper and learn to code in Python.

_"Bloody bad philosophy," grunted Alexandrov. "Waste of breath. Hypothesis judged by prediction. Only sound method."_

Fred Hoyle, the Black Cloud

_“Coding is not for just tech people, it is for anyone who wants to run a competitive company in the 21st century... These are skillsets of the future . . . By better understanding coding, our business teams can speak the same language as our technology teams, which ultimately drives better tools and solutions for our clients.”_

Mary Callahan Erdoes, head of JPMorgan Asset Management october 2018


## Create an environment
To run the jupyter notebook you can create an environemnt that contains the pacakages listed in the file Environment_list.txt. For example in using conda

```
conda create -n myenv --file package-list.txt
```
## Introduction
A short history a econometrics methods in Macroeconomics. In this introductory class we follow Cristopher Sims 2011 Nobel lecture and present a condensed summary of the history of tought of empirical macroeconomics. We also reproduce Haavelmo 1943 model and present maximum likelihood and bayesian methods to estimate it.

[Introduction Slides ](https://github.com/hyperfra/Empirical_Macroeconomics/blob/master/Slides/Class1EM2020.pdf)

[Class 1 Notebook ](https://github.com/superfranci/Empirical_Macroeconomics/blob/master/Notebooks/Class1.ipynb)

Reference

Sims Cristopher A., “STATISTICAL MODELING OF MONETARY POLICY AND ITS EFFECTS”, Nobel Lecture 2011

## Fundamental shocks: VAR and SVAR
A short introduction to VAR and SVAR. The "probabilistic approach" justify under some conditions the estimation of the distribution of the data with a VAR. The "time-series approach" reaches the same conclusions trough the Wold decomposition. The latter approach is more intuitive to identify the type of shocks that can be recovered through a VAR.

[Class 2 Slides ](https://github.com/hyperfra/Empirical_Macroeconomics/blob/master/Slides/Class2EM2020.pdf)

[Class 3 Slides ](https://github.com/superfranci/Empirical_Macroeconomics/blob/master/Slides/Class3EM2020.pdf)

[Class 4 Notebook ](https://github.com/hyperfra/Empirical_Macroeconomics/blob/master/Notebooks/class4.ipynb)

References

James D. Hamilton “Time Series Analysis” 1994 Princeton University Press. 

Sims, Christopher A. 1980. “Macroeconomics and Reality.” Econometrica. January, 48:1, pp. 1– 48.

Olivier Jean Blanchard and Danny Quah. The Dynamic Effects of Aggregate Demand and Supply Disturbances. The American Economic Review , Vol. 79, No. 4 (Sep., 1989), pp. 655-673

## Non-Fundamental shocks: SVAR and FAVAR
Non invertibility, Non-Fundamentalness, Kalman Filter, FAVAR, Factors.

[Class 5 Slides ](https://github.com/hyperfra/Empirical_Macroeconomics/blob/master/Slides/Class5EM2020.pdf)

[Class 6 Slides ](https://github.com/hyperfra/Empirical_Macroeconomics/blob/master/Slides/Class6EM2020.pdf)

References

James H. Stock, Dynamic Factor Models. Oxford Handbook of Economic Forecasting, Michael P. Clements and David F. Hendry (eds), Oxford University Press. 2011

Lippi, Marco and Lucrezia Reichlin. The Dynamic Effects of Aggregate Demand and Supply Disturbances: Comment. American Economic Review 83(3), 644-652.

Fernández-Villaverde, Jesús, Juan F. Rubio-Ramírez, Thomas J. Sargent and Mark W. Watson. 2007. ABCs (and Ds) of Understanding VARs. American Economic Review, 97(3):1021-1026.

Mario Forni, Luca Gambetti and Luca Sala, No news in Business Cycles. The Economic Journal, 124 (December), 1168–1191 December 2013.

(*)Bernanke, Ben, Jean Boivin, and Piotr Eliasz. 2005. Measuring the Effects of Monetary Policy: A Factor-Augmented Vector Autoregressive (FAVAR) Approach Quarterly Journal of Economics 120(1), 387-422.Link


