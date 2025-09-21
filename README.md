# Shadowfox-Intermediate-Task-01
• Developed an algorithm to calculate the Air Quality Index (AQI) for hourly pollutant values and assigned corresponding labels based on established guidelines.
• Constructed a predictive model using the Random Forest Regressor algorithm to accurately forecast the AQI, leveraging insights gained from exploratory data analysis (EDA) and comprehensive dataset preprocessing techniques.
• Evaluated the performance of the predictive model on previously unseen data, achieving an impressive accuracy rate of 82% and demonstrating its robustness and reliability.

Click Below For Checking In Goggle Colab-

[Colab](https://colab.research.google.com/drive/1dkSfh0-Hp9pA5aYBQidVV9JsAde0w8ix#scrollTo=YQR_JSc6CDDH)

# Addition of AQI labels based on AQI values
![image](https://github.com/vannalevaibhav-rcb/AirQualityIndex/assets/53923590/83fdfa4c-d81b-485f-8677-d6dac01f875c)

# AQI distribution 
![image](https://github.com/vannalevaibhav-rcb/AirQualityIndex/assets/53923590/efec72f3-6c7a-4aba-99a0-eae51e36b51f)
</br>The majority of the data points have AQI's between 0 and 150 which means that the livability condition is between Good and Unhealthy for sensitive groups.

# EDA
![image](https://github.com/vannalevaibhav-rcb/AirQualityIndex/assets/53923590/5f487b49-0ff6-424d-ae4b-de36398796aa)
</br>The concentration of CO in the atmosphere is greater during the weekdays of winter and autumn as compared to the weekends in those seasons, because a lot less number of trains and cars are running on weekends to commute people to and from their work.
</br>Summer and Monsoon have similar concentrations of CO during the weekdays and the weekends.
</br>As compared to other seasons, Monsoons are rightly the least polluted ones which makes sense because a lot of pollution matter are washed away from the atmosphere, flowing away the rain into the ground.



# Accuracy of RandomForrestRegressor
There were 2907 number of labels correctly predicted in the test dataset out of 3643 instances, with an error scope of 16.<br>
Accuracy Percentage :  79.79687071095252

