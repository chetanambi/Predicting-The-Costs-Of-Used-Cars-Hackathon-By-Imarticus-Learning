# Predicting The Costs Of Used Cars Hackathon By Imarticus Learning

![image](https://user-images.githubusercontent.com/37707687/61587289-09919480-aba5-11e9-9b79-015a310f40b9.png)

Driverless cars are getting closer to reality and at a faster pace than ever. But it is still a bit far fetched dream to have one in your garage. For the time being, there are still a lot of combustion and hybrid cars that roar around the road, for some it chills. Though the overall data on sales of automobiles shows a huge drop in sales in the last couple of years, cars are still a big attraction for many. Cars are more than just a utility for many. They are often the pride and status of the family. We all have different tastes when it comes to owning a car or at least when thinking of owning one.

Well here of course as the name suggests we are not concentrating on a new car, rather our interest is in knowing the prices of used cars across the country whether it is a royal l luxury sedan or a cheap budget utility vehicle. In this hackathon, you will be predicting the costs of used cars given the data collected from various sources and distributed across various locations in India.

Let’s see if your data science skills can help you predict the price of a used car based on a given set of features discussed below.

Size of training set: 6,019 records

Size of test set: 1,234 records

# FEATURES
    Name: The brand and model of the car.
    Location: The location in which the car is being sold or is available for purchase.
    Year: The year or edition of the model.
    Kilometers_Driven: The total kilometres driven in the car by the previous owner(s) in KM.
    Fuel_Type: The type of fuel used by the car.
    Transmission: The type of transmission used by the car.
    Owner_Type: Whether the ownership is Firsthand, Second hand or other.
    Mileage: The standard mileage offered by the car company in kmpl or km/kg
    Engine: The displacement volume of the engine in cc.
    Power: The maximum power of the engine in bhp.
    Seats: The number of seats in the car.
    New_Price: The price of a new car of the same model.
    Price: The price of the used car in INR Lakhs.

# Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the predicted value and observed score values. The final score calculation is done in the following way:

Submissions are evaluated on Root-Mean-Squared-Log-Error (RMSLE) error = RMSLE (error)

Score = 1 – error

# Leaderboard
Rank 5 (Score: 0.9473)
