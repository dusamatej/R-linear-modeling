# R-linear-modeling
I completed this work for my final in the Statistical Modeling class during the spring 2024 semester. I chose to make a linear regression model predicting the Healthy life expectancy at birth based on a number of
variables. Furthermore, I chose to filter only the data regarding Slovakia. By eliminating other countries from the
model I believe I can get a better result in my model, make it more specific and applicable.

Firstly, before starting to build the model, I checked the independent variables for multicolinearity. The correlation matrix showed no highly correlated independent variables. Therefore, we can continue with the next step.

Once multicolinearity is checked, I went ahead and built the linear model. The model showed only one statistically significant independent variable, the log GDP per capita. This showed me that some of the variables need to be removed. I removed the non-signficant variables one-by-one starting from the highest p-value to the lowest. At the end, I was only left with the log GDP per capita with a statistically significant p-value.

Next, I checked the assumptions. The small sample size brought up challenges in the consideration of linearity, but ultimately I could make decisions with high precision. The plot of residuals vs fitted values seem doesn’t show a non-linear relationship. The partial plot of the independent and dependent variable was considered linear. The boxplot showed 2 outliers, but since there was no reason to believe they should be removed. I left them in. The plot for checking the homoskedasticity of residuals showed linearity.

Upon going over the whole process of building the model and seeing that the model is valid. The results of the model are p=2.75x10^-6, F=88.67, R^2=0.8987, adjusted R^2=0.8885.

The linear regression equation is: healthy life expectancy at birth = -27.83 +9.33*log GDP per capita

Creating knowledge about happiness would start with gathering data, many times through surveys, experiments, and then sharing it publicly for everyone This data is carefully analyzed and put together into a report that goes through peer review before it’s published in a scholarly journal. This diffiicult process gives credibility but reaches mainly experts and academics at first. Over time, as the findings of the study are shared better, they can influence not just further research, but also real-world policy and public opinion. This can have a significant impact despite the specialized start.
