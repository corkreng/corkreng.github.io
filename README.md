

## Projects

### Flight Cancellation Prediction (2 classes - classification | SAS, SQL)
<https://github.com/corkreng/Data-Science-Projects/tree/343963b887fd2b1f453b59ed6809f221de40957b/Flight_cancellation>

 This Project was a combined final project of two different classes during my Master's. The project was to be done in SAS enterprise miner and SAS programming with a three-person group. It was a group project for which I was solely responsible for SAS programming and exploratory data analysis. It included joins using different foreign keys, summary tables, data cleaning, and thorough analysis of variables to determine if they should be included in the modeling process. I identified a strong class imbalance and created a modified sample which split the data into 50% canceled flights and %50 non-canceled flights and set the prior probability with SAS enterprise miner. I assisted in the modeling within SAS Enterprise Miner.
  
### Diabetes Survey Prediction (3 classes- classification | Python, scikit-learn, TensorFlow)
<https://github.com/corkreng/Data-Science-Projects/tree/4b3a35310f78e3d57d4e0a1dc991dd6a502c254c/diabetes_prediction>

  This project was initially created to detect diabetes and prediabetes in individuals who are unaware or likely to have diabetes. Using survey data and questions, I created a predictive model that can be put into production by answering the survey questions and receiving the predicted response. Many models were tried with the logistic regression and deep learning models the same f1-score as well as recall and precision. The logistic regression was chosen as the final model due to its interpretability and lower number of input variables.  

### Dashboard of Presidential Elections (Tableau)
<https://github.com/corkreng/Data-Science-Projects/tree/main/Election_Map_Tableau>

  This project was done with Tableau to show data visualization of previous presidential elections from 1976 to 2020. The dashboard displays results for each state and year specified. 

### Groundwater Forecasting (Time Series Analysis | R, ARMA, HMM, ARMA-GARCH Hybrid)
<https://github.com/corkreng/Data-Science-Projects/tree/fef1ce48c4ba765be2421ca251e606553f94dcd1/GroundWater_forecast>

 This project was done for a consulting class where I consulted the geological survey of Alabama on a time series analysis project. The data given to me was a daily measurement of the height of the water level in a well in Tuscaloosa County. I was tasked with answering a few questions regarding the trend, seasonality, rain as an external regressor, and forecasting. The entire project was done in R using forecast and dplyr libraries. Decomposition showed no trend and showed seasonality having a big impact on the times series data. The auto Arima function was applied with the external regressor and feature-engineered variants, which produced a lower validation MASE score than the naive forecast. It suffered from non-constant variance of residuals in the winter period. In an attempt to address this problem, other external variables associated with the winter season, such as temperature and wind speed, were tried. All models suffered from non-constant variance of residuals in the winter period. All external regressors were statistically significant but more analysis needs to be conducted to create a statistical model that is more accurate for the more volatile winter periods.

 Further analysis has already concluded a high likelihood that there are two different states or probability distributions. This was found through data visualization and a Hidden Markov Model. One state has a high mean and lower variance correlated with Late Spring/Summer/Fall. The other state has a lower mean and higher variance correlated with Winter/Early Spring. The Hidden Markov Model is a poor model due to the lack of accounting for seasonality, the transition probability matrix is static and does not account for the correlation of states and seasons. Additional adding more states improves accuracy suggesting a moving mean. 
 
 Final Analysis
The final analysis will include an GARCH model. 

### Monte Carlo Presidency (Monte Carlo Simulation | R, dyplr)
<https://github.com/corkreng/Data-Science-Projects/tree/main/miniProjects/MonteCarloPresidency>

This project uses simulated polling data from each state's election results of the 2024 election. 
One method assumes independence of states so that the CLT can be used to create a distribution of proportions. A Monte Carlo simulation is then conducted to randomly sample from each state's CLT distribution and transform it into the appropriate amount of electoral college votes. The resulting histogram shows the frequency of electoral college votes for the Republican party. The other method assumes correlation among states. Previous election data was collected and used to create a covariance matrix which is then used as the sigma for the multivariate normal distribution with a mean equal to the simulated proportions. A Monte Carlo simulation is conducted to create a histogram showing the frequency of electoral college votes for the Republican party. The most optimal method would to be use polling data from various sources, adjusting for historical biases, and then creating a covariance matrix with an aggregated mean of proportions. 

 
 
## Etc 
<https://github.com/corkreng/Data-Science-Projects>

  More projects can be found in the Data science projects repository. 




  
