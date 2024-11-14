<center><h1 align="center">MLZoomcamp 2024 Midterm Project.</h1></center>

# CaBi-Bikeshare-Prediction

<center><h2 align="center">1A. Description of the problem and potential models</h2></center>

Washington D.C.'s Capital Bikeshare (CaBi) program has hit [record ridership for the past five months consecutively](https://www.arlnow.com/2024/10/15/e-bikes-fueling-record-setting-local-ridership-numbers-for-capital-bikeshare/). Biking and bikeshare infrastructure in the D.C. Metro area is on its way to becoming as strong as it needs to be to support the increase in ridership, but CaBi is reliant on the help of Bike Angels to help transport bikes to and from stop locations based on how few or overcrowded a docking location may be. Additionally, e-bikes can be docked outside of docking locations, making their availability at centralized locations even more difficult.

This project seeks to perform the following objectives: 
### Demand Forecasting
1. Create a demand model that predicts high demand locations based on time, day, and other variables that can help Bike Angels know where to put more bikes or potentially where to put more docking locations of CaBi. (Linear Regression Model - Lasso/Ridge)

### Neighborhood Level E-Bike Parking
2. Develop a model that can predict where an e-bike can be parked based on where it was picked up. (E.g. ending locations based on neighborhood pickup location and other variables in D.C. I may be using Census Blocks instead, but we will experiment with this). (Logistic Regression or other Ensemble model)

<center><h2 align="center">1B. Description of Dataset</h2></center>
Utilizing [Capital Bikeshare Data Trip History Dataset](https://capitalbikeshare.com/system-data). This data comes directly from Capital Bikeshare that contains individual bike ride data that has starting location and ending location. They have many years of data, but I will be using 2023-2024 to model for 2025. 

<center><h2 align="center">2. Exploratory Data Analysis</h2></center>
1. Duration and frequency of trips based on `Member Types` 
2. How holidays, seasons, work-week vs weekend use, and daily/weekly weather affect bikeshare utilization 
3. How the distribution of member type varies across D.C. neighborhoods 
4. Based on the member type by neighborhood, also where destinations tend to go based on weekday and weekend trips 
5. What stations in D.C. tend to have the highest rates of undocked bikes

This will all culminate on a model that predicts trip duration or which exit stations tend to have the highest rates of non-station parked bikes. 

<center><h2 align="center">3. Model selection and tuning</h2></center>

# Web Service Deployment

# Service Deployment to the Cloud *Bonus*