rr_project In our project we will try to reproduce kaggle project. Below you can find the data set and details of project: https://www.kaggle.com/code/shirantha/bank-marketing-data-a-decision-tree-approach Our project will be written in R compared to original python code.

As part of the project we:
1. transformed project from python to R
2. ensured code is reproducible
  - added library verification and fixed versions of libraries
  - ensured data is loaded from UCI repo (original site where dataset was uploaded) instead of kaggle
  - added more code comments to enable more explainability
  - fixed the seed
3. created different model
4. increased number of observations used for predicting with ml from 11k on kaggle to 45k
5. fixed the mistake of balancing test data
6. change the dataset used to complete dataset from the original source

Project outcome:
We did manage to reproduce the project in different code language, however we achieved different results. Difference results from original author not fixing seed used by machine learning functions.

