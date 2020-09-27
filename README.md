# Healthcare Analysis in times of COVID-19 (India)
This is an **EDA and a Machine Learning project** which utilses the **COVID-19** statewise data available on https://api.covid19india.org/ for India. 

## Basic Visualization of Data
The following plot was plotted using plotly and shows the daily positive cases till 15th of July.
![Daily cases in India till 15th of July](https://github.com/Vidushi-Gupta/COVID_hospital_beds/blob/master/Visualizations/daily%20cases.png)

The following plot was plotted using plotly and shows the daily cured cases till the 15th of July.
![Daily cured cases in India till 15th of July](https://github.com/Vidushi-Gupta/COVID_hospital_beds/blob/master/Visualizations/cured%20cases.png)

## Predicting using ML Model- FB Prophet
Using the Facebook Prophet model, the confirmed number of COVID-19 cases were predicted for a period of 48 days making the prediction upto 25th July.
Following shows the components of the plot.
![plot components](https://github.com/Vidushi-Gupta/COVID_hospital_beds/blob/master/Visualizations/plot%20components.png)

This shows the weekly trends and the predictions that the model forecasted.
The following graph shows the changepoints in the trend that were observed along with the prediction by the model

![changepoints](https://github.com/Vidushi-Gupta/COVID_hospital_beds/blob/master/Visualizations/changepoints.png)

The r2 score for the model was found to be 0.8233 which gives an accuracy percentage of the model to be about 82.33 percent.

## Comparison: Confirmed cases with hospital beds available
The following plot demonstrates the relationship between the confirmed and the deceased cases with the number of hospital beds available in each state in India.
![Comparison](https://github.com/Vidushi-Gupta/COVID_hospital_beds/blob/master/Visualizations/beds.png)


## Conclusions
The plot clearly shows that in the most affected places, there has been a considerable amount of shortage of hospital beds for the COVID patients thereby making home isolation a better option for the patients.


You're most welcome to use the datasets attached here or to fork the repository.

Happy Visualizing!
