# CSE523-Machine-Learning-Amigos
## Project Introduction:
Our project is to predict the weather specifically for Ahmedabad city. We collected the historical weather data of each day from 2015 to 2020 specifically of Ahmedabad City. The data-set included various features related to weather.
For weather prediction we chose Regression as the machine learning algorithm, as our weather data has real values, so the best algorithm for predicting temperature was Regression. There are many regression techniques and we tried some of them for testing and compare the accuracy of the prediction. First of all we tried Multiple Linear regression and in which we got good accuracy and after that we tried Polynomial, Lasso and Ridge regression. We got very interesting results in all of them.
First of all, we started with predicting the temperature and we looked for the model which give us best accuracy. After doing that, we move on to rainfall prediction. And at last, for weather prediction, many features are dependent on each other so we can take one or more features as dependent feature and predict the output. We thought of predicting humidity along with temperature, so we used Multivariate Regression to predict the same.



## Results:



Multivariate_regression

![Multivariate_regression](https://user-images.githubusercontent.com/60286639/114300979-4b344280-9ae0-11eb-801e-7c0bbe5174ec.png)

p_values of Backward Feature Elimination


![p_values](https://user-images.githubusercontent.com/60286639/114300982-4c656f80-9ae0-11eb-82ea-4b2e88e34936.jpeg)

Polynomial_temperature_prediction


![Polynomial_temperature_prediction](https://user-images.githubusercontent.com/60286639/114300983-4cfe0600-9ae0-11eb-834a-b3e820cd5f63.png)

Rainfall_prediction


![rainfall_prediction](https://user-images.githubusercontent.com/60286639/114300985-4cfe0600-9ae0-11eb-9e48-1cce92c3bb03.png)

Accuracy of all the Regreesion Algorithms


![Accuracy](https://user-images.githubusercontent.com/60286639/114300986-4d969c80-9ae0-11eb-83b4-b8a2b21cf334.jpeg)

Extra_tree_classifier 


![Extra_tree_classifier](https://user-images.githubusercontent.com/60286639/114300987-4d969c80-9ae0-11eb-9703-8b9649fc91e8.jpeg)

heatmap of correlation


![heatmap](https://user-images.githubusercontent.com/60286639/114300988-4e2f3300-9ae0-11eb-8296-6f6e50697066.png)

information_gain


![information_gain](https://user-images.githubusercontent.com/60286639/114300990-4e2f3300-9ae0-11eb-871c-ea0352f74e1f.jpeg)


## References:

[1] Ahmedabad Historical Weather. Worldweatheronline.Com,
2021, https://www.worldweatheronline.com/ahmedabad-weatherhistory/
gujarat/in.aspx. https://dzone.com/articles/hashmap-


[2] Paras, Sanjay Mathur. ”A simple weather forecasting model using
mathematical regression.” Indian Research Journal of Extension Education
12, no. 2 (2016): 161-168.


[3] ”What Is The Pearson Coefficient?”. Investopedia, 2021,
https://www.investopedia.com/terms/p/pearsoncoefficient.asp.


[4] Folorunsho, Olaiya Adeyemo, Adesesan. (2012). Application of Data
Mining Techniques in Weather Prediction and Climate Change Studies.
International Journal of Information Engineering and Electronic
Business. 4. 10.5815/ijieeb.2012.01.07.


[5] ”Mathematics for Machine Learning”. Copyright 2020 by Marc Peter
Deisenroth, A. Aldo Faisal, and Cheng Soon Ong. Published by
Cambridge University Press.


[6] T. Anjali, K. Chandini, K. Anoop and V. L. Lajish, ”Temperature Prediction
using Machine Learning Approaches,” 2019 2nd International
Conference on Intelligent Computing, Instrumentation and Control
Technologies (ICICICT), Kannur, India, 2019, pp. 1264-1268, doi:
10.1109/ICICICT46008.2019.8993316.


[7] Sharaff, Aakanksha Gupta, Harshil. (2019). Extra-Tree Classifier
with Metaheuristics Approach for Email Classification. 10.1007/978-
981-13-6861-5-17.


[8] Alhaj TA, Siraj MM, Zainal A, Elshoush HT, Elhaj F
(2016) Feature Selection Using Information Gain for Improved
Structural-Based Alert Correlation. PLoS ONE 11(11): e0166017.
https://doi.org/10.1371/journal.pone.0166017.


[9] Sutter, J. and Kalivas, J., 1993. Comparison of Forward Selection,
Backward Elimination, and Generalized Simulated Annealing for
Variable Selection. Microchemical Journal, 47(1-2), pp.60-66.


[10] Ibrahim, Nuhu Hamid, H.A. Rahman, Shuzlina Fong, Simon.
(2018). Feature selection methods: Case of filter and wrapper approaches
for maximising classification accuracy. Pertanika Journal of
Science and Technology. 26. 329-340.


[11] A. Shetye, Medium. [Online]. Available:
https://towardsdatascience.com/feature-selection-with-pandase3690ad8504b.
[Accessed: 11-Apr-2021].
