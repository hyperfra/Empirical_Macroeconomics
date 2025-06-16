# Empirical Macroeconomics: the identification of shocks
This course provides a non-systematic account of a range of research methods in empirical macroeconomics to identify shocks. It is intended as an apprenticeship to students interested in working in research departments. Students will reproduce the results of three published paper and learn to code in Python.

Starting in 2025 we will integrate GEN AI in the course to deepen student learning and understanding. When students are implementing time series models from the papers, they could use GEN AI to:

- Debug their code with detailed explanations of what might be going wrong and why
- Get step-by-step guidance on translating the mathematical equations from papers into Python code
- Have their code reviewed with suggestions for improvement in both functionality and style

Students might also consider using GEN AI to create individualized learning paths. For example, if a student is struggling with understanding stationarity concepts, GEN AI can provide tailored explanations and generate specific examples using their actual data. For this to work we will need to learn how to effectively phrase questions to get the most helpful responses for econometric implementation.

_"Bloody bad philosophy," grunted Alexandrov. "Waste of breath. Hypothesis judged by prediction. Only sound method."_

Fred Hoyle, the Black Cloud

_“Coding is not for just tech people, it is for anyone who wants to run a competitive company in the 21st century... These are skillsets of the future . . . By better understanding coding, our business teams can speak the same language as our technology teams, which ultimately drives better tools and solutions for our clients.”_

Mary Callahan Erdoes, head of JPMorgan Asset Management october 2018


## Create an environment
To run the jupyter notebook you can create an environemnt that contains the pacakages listed in the file Environment_list.txt (created in the first notebook). For example in using conda

```
conda create -n myenv --file package-list.txt
```
## Colab
The 2025 course starts using Colab and the integrated Gemini agent


## Introduction
A short history a econometrics methods in Macroeconomics. In this introductory class we follow Cristopher Sims 2011 Nobel lecture and present a condensed summary of the history of tought of empirical macroeconomics. We also reproduce Haavelmo 1943 model and present maximum likelihood and bayesian methods to estimate it.

[Introduction html](https://hyperfra.github.io/EmpiricalMacroClass1/)

[Class 1-2 Colab ](https://colab.research.google.com/drive/1jX0r00MmvVU6BWQEl1FE4AAiw66iOkMX?usp=sharing)

Reference

Sims Cristopher A., “STATISTICAL MODELING OF MONETARY POLICY AND ITS EFFECTS”, Nobel Lecture 2011

## Fundamental shocks: VAR and SVAR
A short introduction to VAR and SVAR. The "probabilistic approach" justify under some conditions the estimation of the distribution of the data with a VAR. The "time-series approach" reaches the same conclusions trough the Wold decomposition. The latter approach is more intuitive to identify the type of shocks that can be recovered through a VAR.

[Class 3 Slides html](https://hyperfra.github.io/EmpiricalMacroClass2/)

[Class 3-5 Colab](https://colab.research.google.com/drive/1e1by4__4V3XiURZLFhgbLF4CAaqkklim#scrollTo=kDOj6bWtmuHs)

[Problem set 1](https://colab.research.google.com/drive/1SP0WS-COMTWkubbj58gcsdS-rPGMhbYI?usp=sharing)

[prompt for Var resolution](https://github.com/hyperfra/Empirical_Macroeconomics/blob/master/data/Prompt_for_VAR_resolution.pdf)
 

References

James D. Hamilton “Time Series Analysis” 1994 Princeton University Press. 

Sims, Christopher A. 1980. “Macroeconomics and Reality.” Econometrica. January, 48:1, pp. 1– 48.

Olivier Jean Blanchard and Danny Quah. The Dynamic Effects of Aggregate Demand and Supply Disturbances. The American Economic Review , Vol. 79, No. 4 (Sep., 1989), pp. 655-673 [Link](https://www.jstor.org/stable/2117539)

## Non-Fundamental shocks: SVAR and FAVAR
Non invertibility, Non-Fundamentalness, Kalman Filter, FAVAR, Factors.

[Class 6-8 Slides html](https://hyperfra.github.io/EmpiricalMacroClass3/)

[Class 6-8 Colab](https://colab.research.google.com/drive/1MeyDcFZRYYsm3Rt7dSXFFmbjo3E9YqXV?usp=sharing)

[Problem set 2](https://colab.research.google.com/drive/1HiD2ebjUxhKKWHoATx_IX3HpdXJz3NNl?usp=sharing)

[prompt for code improvement](https://github.com/hyperfra/Empirical_Macroeconomics/blob/master/data/prompt_for_code_improvement.pdf)
 
 


References

James H. Stock, Dynamic Factor Models. Oxford Handbook of Economic Forecasting, Michael P. Clements and David F. Hendry (eds), Oxford University Press. 2011

Lippi, Marco and Lucrezia Reichlin. The Dynamic Effects of Aggregate Demand and Supply Disturbances: Comment. American Economic Review 83(3), 644-652.

Fernández-Villaverde, Jesús, Juan F. Rubio-Ramírez, Thomas J. Sargent and Mark W. Watson. 2007. ABCs (and Ds) of Understanding VARs. American Economic Review, 97(3):1021-1026.

Mario Forni, Luca Gambetti and Luca Sala, No news in Business Cycles. The Economic Journal, 124 (December), 1168–1191 December 2013.

(*)Bernanke, Ben, Jean Boivin, and Piotr Eliasz. 2005. Measuring the Effects of Monetary Policy: A Factor-Augmented Vector Autoregressive (FAVAR) Approach Quarterly Journal of Economics 120(1), 387-422. 
[Link](https://academic.oup.com/qje/article-abstract/120/1/387/1931468?redirectedFrom=fulltext)


## Non-recoverable shocks: Kalman and Structural Models
News, Kalman Filter. Invertibility problems concerns shocks observed by agents. What if agents cannot observe fully the shocks.

[Class 8-12 Slides html](https://hyperfra.github.io/EmpiricalMacroClass4/)

[Class 8-12 Colab ](https://colab.research.google.com/drive/1cl8ss5LQKkiwYToQR9Yfs1VrmLRF2MyS?usp=sharing)

[Problem Set 3](https://colab.research.google.com/drive/1hM_mgFjyoJV79EpddJ8_6eQmkDtEkxLJ?usp=sharing)

References

James D. Hamilton Time Series Analysis 1994 Princeton University Press.

(*)Blanchard, Olivier J., Jean-Paul L'Huillier and Guido Lorenzoni. 2013. News, Noise, and Fluctuations: An Empirical Exploration American Economic Review, 103(7):3045-70.[Link](https://www.aeaweb.org/articles?id=10.1257/aer.103.7.3045)

