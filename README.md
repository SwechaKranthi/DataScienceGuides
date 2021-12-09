# DataScienceGuides
This repository is a space for me to document and develop systems for optimizing data science practices


### Cheatsheets: 
1. Probability:
  - https://github.com/wzchen/probability_cheatsheet 
2. Statistics:
  - https://stanford.edu/~shervine/teaching/cme-106/cheatsheet-statistics 
3. SQL: 
  - https://learnsql.com/blog/sql-basics-cheat-sheet/sql-basics-cheat-sheet-a4.pdf
4. Pandas:
  - http://datacamp-community-prod.s3.amazonaws.com/dbed353d-2757-4617-8206-8767ab379ab3 
5. Visualization:
  - http://www.biosci.global/customer-stories-en/data-visualization-cheat-sheet/ 
6. Matplotlib:
  - https://datacamp-community-prod.s3.amazonaws.com/28b8210c-60cc-4f13-b0b4-5b4f2ad4790b 
7. Machine Learning:
  - https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning
8. NLP:
  - https://cheatography.com/sree017/cheat-sheets/nlp/
  - https://cheatography.com/murenei/cheat-sheets/natural-language-processing-with-python-and-nltk/ 
9. Jupyter Notebook
  - https://datacamp-community-prod.s3.amazonaws.com/48093c40-5303-45f4-bbf9-0c96c0133c40 


### Cool Tools:
1. Auto - Arima : for time series
  - First, What is Arima
    - 'AutoRegressive Integrated Moving Average', is a forecasting algorithm based on the idea that the information in the past values of the time series can alone be used to predict the future values.
    - So Arima is a class of models that calculate the lags and lagged forecast errors of a time series and is characterized by 3 variables: P, Q ,D
      - p is the order of auto regression variable (AR)
      - q is the order of the Moving Average variable (MA)
      - d is the number of differences needed to make the time series stationary
    - Manually, We define and try to optimize for the pqd values when using arima for univariate series analysis
    - AutoArima is a tool for automatically optimizing for these values
  - ###### Package: https://pypi.org/project/pmdarima/
  - ###### How To: https://towardsdatascience.com/time-series-forecasting-using-auto-arima-in-python-bb83e49210cd
  - ###### Example: https://github.com/SushmithaPulagam/TimeSeries_Auto-ARIMA
