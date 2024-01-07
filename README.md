# Project Name
> # Bike Sharing System Model for BoomBikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
	- BoomBikes deals with bike-sharing systems . A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- What is the background of your project?
	-	- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
	- Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market
- What is the business probem that your project is trying to solve?
    - Linear Regression Method to find which variables are significant in predicting the demand for shared bikes.
    - Perform test prediction and find how well those variables describe the bike demands
    - The output model explains demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
- What is the dataset that is being used?
	- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
 	- A dataset is provided, with three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number casual users who have made a rental. The variable 'registered' on the other hand shows the total number of registered users who have made a booking on a given day. Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. The model should be built taking this 'cnt' as the target variable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- An increase of temp will increase the bike request.
- An increase in years will increase the bike request. This might be due to increase in popularity with passing years.
- Weather, which is referred as " Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds ", would lead to lead to decrease in bike request.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.6
- NumPy - version 1.18.1
- Pandas - version 1.2.3
- Matplotlib - version 3.1.3
- Seaborn - version 0.10.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Thanks to IITB and Upgrad team and coach for sharing the knowledge . 
- References 
	-  https://www.python.org


## Contact
* [Smrutirekha Khatua](https://github.com/Smrutirekha90)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->