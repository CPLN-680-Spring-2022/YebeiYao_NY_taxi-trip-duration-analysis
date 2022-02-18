# YebeiYao_NY_taxi-trip-duration-analysis
MUSA capstone in 2022 

## Question proposed
In this project, on the base of the competition held on Kaggle, which is challenging competitors to build a model that predicts the total ride duration of taxi trips in New York City, and combine the [ridershare demand analysis project we conducted in MUSA 508,](https://urbanspatial.github.io/PublicPolicyAnalytics/predicting-rideshare-demand.html#conclusion---dispatch), I'd like to focus on **Spatial problem of space & time taxi ride demand and duration for taxi trip in New York.** 

## Goal and Potential audience
  **Goal**
  1. Identifing specific districts, weather conditon and time period (in a day, a month or in a year) in most need of taxi service.  
  2. Find out the mobility pattern(spatial distance, clustering and time preference serial correlation) and general regularities of taxi trips in New York city.  
  3. Build a linear regression model that could predict the time duration and service demand.  
 
 **Potential audience**
  1.For taxi/ rideshare companies like Uber or Lyft, the result can be helpful for them to predict user supply and demand in a spatio-temperal scape, and make resource allocation more effective to direct drivers to high demand areas before the workload and ride demand exceeds.  
  2.For passengers, the result can help them figure out whether taxi resource are abundant or not when they plan to grab a taxi.  
  Additionally, based on the start point and end point of the upcoming trip, it is easy to predict how much time it is required for the trip, and they can leave enought time for the taxi trip in advance.  
  3.Especially in extreme weather and rush hour, when the time consumption is hard to estimate, so with the help of the model I build based on the trip data, it will be easy to predict how much time it will be, to travel from point A to point B under specific condition.  


## Data 
  1.Taxi trip data in NY-2016 download from Kaggle.  
  2.weather data in NY-2016, extracted from API and Kaggle.  
  3.New York neighborhood and census tract data.  
  4.ACS demographical data, which could be useful in model building.  


## Research method
  1. Exploratory analysis on the taxi trip data itself, mainly for data visualization. (Univariate analysis , bivariate analysis and correlation matrix plots.)  
  2. Machine learning method, combining both spatial model and time series model.  
  3. Linear Regression Model. To split the data into train and test group, and train our dataset to serve for the purpose of predicting the NYC taxi trip duration and spatial/temporal demand in testing dataset to see the accuracy and generalizability.  


## Expected deliverables
  1. Report for the overall findings.  
  2. Dynamic visualization: Animation video or a dashboard to visualize the taxi mobility result,to show as time goes by, how the taxis around city move around.  
  3. Create a dashboard useful in evaluating the potential time consumption of specific taxi trip. When user click of search for the start point and end point of their planning trip, and set the current time and weather conditon, the model will automatically calculate how much time approximately it costs to travel from A to B.  

## Assuming steps in the report
 1.Introduction  
 2.Data cleaning, fixing outliers and strange trip data.  
 3.Data exploratory analysis, with visualization work, to create tables, plots, maps to visualize the current pattern of trip in spatial and time scale.  
 4.Feature engineering, create the panel combining all the feature might influence the time duration and service demand together, for future model building.  
 5.Correlation analysis, Univariate analysis , Bivariate analysis, etc.  
 6.Model building and predition.  
 7.Generalizability and Accuracy tests.  
 8.Create animation of the mobility pattern.  
 9.Final dashboard, to calculate the time consumption under specific weather and time condition.  
 10. Final report completion.  

