# Airline Customer Satisfaction Project 
Customer Satisfaction with Airlines via Machine Learning and Data Science

Presently, the global airline industry comprises more than 5,000 airlines, each assigned an ICAO code. Organization for International Civil Aviation (ICAO). 

Because it is evident that competition among airlines is at an all-time high, consider the possibility that we could gain an advantage over them by utilizing data science. 

Then, let's provide a fundamental plot for our project:  

The aforementioned airline (BEST AIRLINES) has a substantial customer base; however, the source of consumer satisfaction remains unknown to them.

# So our Objectives are :

1) To what extent are customers content?
2) What factors contribute to customers being both dissatisfied and satisfied?
3) Elaborate on potential remedies and additional insights that can be communicated to the airline board.

I began by conducting a cursory examination of the data (the CSV file) and gaining an understanding of it. Consequently, my findings are as follows:

A survey was conducted among more than one hundred thousand airline passengers, during which satisfaction ratings, personal information, flight particulars, and assessments of comfort, hygiene, and service were recorded.

# Passenger Information, include:
      *  Age
      * Type of Travel (Business or Personal)
      * Travel Class (Business, Eco, Eco+)

# Flight Information, include:
      * Flight Distance
      * Departure Delay (minutes)
      * Arrival Delay (minutes)

# Customer experience on services, include:

  * Departure/Arrival time convenient
  * Ease of online booking
  * Online boarding
  * On-board service
  * Check-in service
  * Gate location
  * Baggage handling
  * Seat comfort
  * Food and drink
  * Leg room service
  * In-flight wi-fi services
  * In-flight entertainment
  * In-flight service
  * Cleanliness

First step I took -

Data Preparation (Library Importation) and Data Importation and Pre-Prep


![Screenshot 2024-05-07 at 9 10 05 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/1ecbba42-5615-4c09-ba8f-63da2afe9378)

![Screenshot 2024-05-07 at 9 11 05 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/cb765be3-bde3-44e4-a77d-6323bd57ed06)

So let's View - 

![Screenshot 2024-05-07 at 9 12 19 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/5846fcac-08bb-4bb3-8d86-a2c1c43e50de)

Let's skip ahead and begin the Exploratory Data Analysis by using visualizations to address unanswered issues. First, we will focus on satisfaction. 

The Process - 
![Screenshot 2024-05-07 at 9 33 17 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/2399667f-134c-44d7-88eb-fa6ec7b8637a)

The Visual - 
![Screenshot 2024-05-07 at 9 33 24 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/1d6eda50-269f-47e0-a6c6-dbfabc924df2)


According to the data, 54.7% of individuals expressed satisfaction, while 45.3% expressed dissatisfaction. From my perspective, I have observed that there is limited space available. It is a closely matched comparison. Therefore, how can we determine the specific areas that require modification or enhancement in the airline, as specified by customers in the survey? 

Next, we will explore more visualizations. To do so, I examined the relationship between age and satisfaction. Let's examine the different age groups that are either satisfied or unhappy. 

The Process - 
![Screenshot 2024-05-07 at 9 31 52 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/3152d177-a666-4eed-a095-7bb4ea7d8ed9)

The Visual - 
![Screenshot 2024-05-07 at 9 32 18 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/951c7997-f7a3-4e16-852d-5897b89e02b6)

It is evident that there is a significant disparity in dissatisfaction and satisfaction levels among individuals aged 8 to 38. However, individuals in the age bracket of 40 to 61 experienced a consistently high level of satisfaction, with the majority expressing contentment. What could be the underlying reason for this significant disparity? Let us delve more to uncover this enigma. 

The subsequent step I undertook involved comprehending the various categories of customers participating in our survey. Some of the customers indicated that they were loyal patrons, potentially due to their frequent use of the airline's services and membership in the loyalty program. However, it is evident that not all consumers can be classified as devoted customers. Some customers may be flying out of necessity or making a hasty decision while booking their flight. Therefore, they are uncertain about retaining customers. Let's examine -

The Process - 
![Screenshot 2024-05-07 at 9 45 07 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/2c846755-c41f-4a2e-a9fb-f114a60e088a)

The Visual - 
![Screenshot 2024-05-07 at 9 45 15 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/a9270747-a8d0-4768-9100-62248a140778)

Upon observation, it is evident that loyal consumers exhibit higher levels of satisfaction compared to disloyal customers. Therefore, it can be inferred that clients who are not registered as loyal customers with the airline have a less favorable satisfaction outcome. What could be the rationale for this? One possible explanation, which I can provide without much analysis, is that the benefits offered to loyal consumers may not be accessible to disloyal customers. 

However, the current question remains: What is the purpose of these consumers' travel? Perhaps we can obtain an understanding of individuals' satisfaction levels when traveling for various purposes.

The Process - 
![Screenshot 2024-05-07 at 9 45 23 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/dfb34670-1bcb-4fa6-8236-ee69ffc3f979)

The Visual - 
![Screenshot 2024-05-07 at 9 45 33 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/0c49ea23-e4e0-4425-98b2-fbf0d1e1c748)

It is evident that the satisfaction level was higher in the business class compared to personal travel. Therefore, individuals who traveled for personal reasons had lower satisfaction levels, whereas those traveling for business purposes had higher happiness levels. Now, I believe the most effective approach to go further into this inquiry is to analyze the predominant class in which satisfied individuals were situated. Specifically, we should determine whether they were mostly in business class, economy class, or economy plus class.

The Process - 
![Screenshot 2024-05-07 at 9 55 49 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/e760ad3f-f754-4083-85f4-37634e107598)

The Visual - 
![Screenshot 2024-05-07 at 9 55 57 PM](https://github.com/leandrenash/airlinecustomer/assets/73446394/b8f441b3-6ae4-4d1b-88f2-21d0f18a10a9)





