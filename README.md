# Revenue_Forecasting
Python project on forecasting monthly revenues in of start-ups and scale-ups in B2B SaaS. As the utilized data is confidential, some parts of the code as well as outputs were excluded for the sake of this upload. I chose to compare models from the classes of SARIMA, NeuralProphet and Temporal Fusion Transformer.

This document is meant to provide a short overview of the notebooks that were created as part of my thesis. The folder includes five notebooks, each covering a distinct piece of code that is described below. 

Notebooks: 

EDA: This notebook contains the code that was used for the EDA conducted in Chapter 3.2 of the thesis. It first focuses on an overall comparison of the available datasets in order to derive dataset groups. Next, the notebook includes the code for the individual analyses for the three datasets that were chosen as prototypes, i.e., C4, C1 and C6. 

Models_univariate: This notebook contains the code on the univariate experiments conducted as part of my thesis. Together with the notebook on multivariate models it serves as the baseline both for Chapter 3.4 covering the approach that was pursued in the experiments as well as for Chapter 4 presenting the results from the experiments. Note that the experimentation focused on the prototypes of each dataset group i.e., dataset C4, C6 and C1. 

Models_multivariate: This notebook contains the code on the multivariate experiments conducted as part of my thesis. Together with the notebook on univariate models, it serves as the baseline both for Chapter 3.4 covering the approach that was pursued in the multivariate NP experiments as well as for Chapter 4 presenting the results from the experiments. Note that the experiments only took place on datasets C4 and C6 as the two prototypes that covered enough data to execute the experiments. 
