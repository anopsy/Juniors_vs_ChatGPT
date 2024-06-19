### Analysis of Job Offers for Entry Level positions - Juniors and Interns
I tried to answer the question: Did the ChatGPT (and the rise of LLM's in general) replace Juniors?
  #### 1. [Exploratory Dataset Analysis](https://github.com/anopsy/Juniors_vs_ChatGPT/blob/main/dataset_EDA.md)
  In this document I summarized and visualized my findings about the dataset samples - from 2023 and 2024.
  It contains results of [cleaning](https://github.com/anopsy/Juniors_vs_ChatGPT/blob/main/dry_cleaning.ipynb) and [analysis](https://github.com/anopsy/Juniors_vs_ChatGPT/blob/main/analysis.ipynb).
  #### 2. [Has ChatGPT replaced Juniors and Interns?](https://github.com/anopsy/Juniors_vs_ChatGPT/blob/main/Has%20ChatGPT%20replaced%20Juniors.md)
  This document contains what I discovered while looking for the answer to the main question.


###  Attempt at modelling the estimated compensation using different Regression Models
Additionaly I tried to model the compensation estimation for Engineering Jobs in general (so not only Juniors and Interns)
#### 1. [Baseline Model](https://github.com/anopsy/Juniors_vs_ChatGPT/blob/main/model/dry_baseline.ipynb)
Baseline resulted in 0.661 MSE (the compensation data were scaled) and R2-score of 0.38.
#### 2. [Model Experimentation](https://github.com/anopsy/Juniors_vs_ChatGPT/blob/main/model/model_exp.ipynb)
Experimentation with different regression models resulted in SVR "rbf" achieving mean MSE of 0.6 and mean R2 score of 0.44
        



_Number of Job Offers from 2023 and 2024 data samples, that I obtained from [SourceStack](https://sourcestack.co/)_
![image](https://github.com/anopsy/Juniors_vs_ChatGPT/assets/74981211/fd29a814-0616-4d22-a4cb-8dde936f019d)

#### A. What I did:
1. Data cleaning
2. Data analysis
3. Baseline model
4. Comparison of different regression algorithms and their metrics

#### B. What I haven't done (yet):
1. Hyperparams tuning, I did only validation curve for the best scoring model (SVR"rbf")
2. Feature importances
3. Discussion and explanation of modelling results
