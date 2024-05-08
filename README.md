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

Upon observation, it is evident that the Business class has the highest level of contentment, while both the Economy and Economy Plus classes have the highest level of unhappiness. This suggests that the privileges associated with being in the Business class may be contributing to a decline in overall satisfaction.

to continue with the visualisations I start by iterating over each column in a DataFrame to identify which columns have fewer than 10 unique values, indicating they are likely categorical. For each identified column, I then set up a subplot to prepare for visualization. I calculate the value counts of the column, which help determine the proportions for the pie chart segments.

I proceed by selecting the 'Spectral' color map to assign a unique color to each category based on the number of unique values in the column. To enhance the visual appeal and make the pie chart into a donut chart, I insert a white circle in the center of the pie.

Next, I configure the pie chart to start from a 90-degree angle to orient the chart with the top-most segment beginning from the vertical axis. I add percentage labels to each segment of the pie chart, displaying them at a calculated distance from the center to ensure they are legible and neatly positioned within each segment.

I then add a legend to the plot, aligning category names with their corresponding colors and positioning it for optimal visibility without overlapping the chart. Finally, I title the chart with the name of the column being visualized to clearly indicate what data is being presented. Each chart is displayed one after the other, allowing for a clear and structured presentation of categorical data distributions within the dataset.

The Process - 
![Screenshot 2024-05-08 at 12 49 56 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/26367316-90b8-4065-b9b9-1b29680be4c7)

The Visual - 
![Screenshot 2024-05-08 at 12 51 56 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/6cccca5a-837f-4186-a335-48779427408e)
![Screenshot 2024-05-08 at 12 51 49 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/35d14782-a4f4-4033-83f7-8b0c29f4399e)
![Screenshot 2024-05-08 at 12 51 43 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/62a634f9-7b26-4ceb-b877-3390fec5fe01)
![Screenshot 2024-05-08 at 12 51 37 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/929e0923-faf2-47c3-a96f-47c6f85044b7)
![Screenshot 2024-05-08 at 12 51 29 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/4a1c933a-283c-43c3-9e47-65c5add7630b)
![Screenshot 2024-05-08 at 12 51 22 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/f86667e1-47a8-434b-8a8d-fd9084f9c6d2)
![Screenshot 2024-05-08 at 12 51 13 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/31ab1351-6b07-47fe-b1c9-a43a6f79c7e6)
![Screenshot 2024-05-08 at 12 51 03 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/fa75670f-bfd9-46f0-9db7-fa5dea5b32da)
![Screenshot 2024-05-08 at 12 50 52 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/ff59066c-05c1-4d02-abee-b26d111c4b9a)

Continuing from the visualization of categorical data, let's further explore the columns in the DataFrame that contain more than 10 unique values, suggesting they are numerical or have a wider range of categories. For each of these columns, I initiate by creating a subplot with two panels for different types of visualizations: a histogram and a boxplot, arranged side by side within a figure that measures 12 by 4 inches.

For the histogram part, I calculate the value counts of the column and use seaborn's histplot to plot these values. I set the color of the histogram to yellow for clear visibility. The histogram is placed in the first panel (ax[0]), and I title it with the column name to indicate which data it represents.

Next, I use seaborn’s boxplot to create a boxplot in the second panel (ax[1]). This boxplot compares the distribution of the column's values against the 'satisfaction' category in the DataFrame, using a 'Spectral' color palette for visual distinction. This setup helps in examining the relationship between the numerical data and passenger satisfaction levels, providing insights into how different values within a column correlate with satisfaction.

Each pair of visualizations is then displayed, showing the distribution and data spread for each column with more than 10 unique values. This allows for a comprehensive view of the data's characteristics, helping to identify trends, outliers, and central tendencies within the dataset. This method of visualization is crucial for deeper data analysis and interpretation in exploratory data studies.

The Process - 
![Screenshot 2024-05-08 at 12 53 40 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/143d2d9d-c581-405c-9e55-2022e611f89e)

The Visual - 
![Screenshot 2024-05-08 at 12 54 32 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/19a1c428-d7d8-4f4a-9b48-5e004cd03d21)
![Screenshot 2024-05-08 at 12 54 21 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/13adbe58-a926-4f80-a931-ee8ad2893b52)

Continuing from our exploration with histograms and boxplots for columns with more than 10 unique values, let's delve deeper into the statistical properties of the numerical data in our DataFrame. I employ the describe() method on the DataFrame, specifying additional percentiles—75th, 90th, 95th, and 98th—to gain a broader understanding of the distribution characteristics of each numerical feature.

By calling df.describe() and including these specific percentiles, I aim to obtain detailed descriptive statistics that go beyond the typical measures. This approach provides insights into the quartiles, thus highlighting where the majority of data points lie and identifying how spread out the higher values are. For instance, seeing the values at the 90th, 95th, and 98th percentiles helps in understanding potential outliers and the tail behavior of the distribution.

This detailed statistical summary includes the count, mean, standard deviation, minimum, and the specified percentile values for each numerical column in the DataFrame. The percentiles I choose are particularly useful in scenarios where the data distribution is skewed or when planning capacity and assessing risk scenarios based on data-driven thresholds.

By analyzing these expanded statistics, we are better equipped to make informed decisions, tailor strategies to handle outliers, and assess the risk of extreme values in our data. This method enhances our analytical capabilities by providing a more nuanced view of the dataset's numerical features.

The Process - 
![Screenshot 2024-05-08 at 12 57 55 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/8ac89668-2668-44c2-9412-122c066378fa)

The Visual - 
![Screenshot 2024-05-08 at 12 58 01 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/23ef0e49-03c9-40b2-b138-fd99dd1fa740)

.... Fast forwarding a bit.....

Let's now focus on enhancing our machine learning data preparation by transforming categorical variables into a format that can be easily used by algorithms. This involves encoding categorical columns to numeric using the OneHotEncoder from Scikit-learn, which is a critical step for models that only accept numerical input.

I start by importing the OneHotEncoder from the sklearn.preprocessing module. This encoder is chosen because it converts categorical variable(s) into a set of binary variables, one for each category, which is ideal for handling nominal data without imposing ordinal assumptions.

With the encoder in place, I initialize it with sparse=False to ensure the output is a dense array, which is easier to work with in a pandas DataFrame context. Then, I proceed to fit the encoder to the columns specified in encode_cols of the X_train dataset. Fitting the encoder involves learning the unique categories per column to prepare for transforming these into binary vectors.

Once fitted, I use the encoder to transform these columns, effectively creating a matrix where each row corresponds to an observation and each column represents a category from the original data encoded as binary. This transformation is vital for preparing the data for machine learning algorithms, which require numerical input and benefit from categorical variables being distinctly represented to capture the essence of their contribution to the dataset.

The resulting binary matrix is then converted into a DataFrame for better handling and integration with other data processing steps. This DataFrame, encoded_df, now contains new columns named according to the unique categories identified by the encoder, prefixed appropriately to indicate their origin. This makes it easy to track back to the original categorical variables.

By using the OneHotEncoder and creating this encoded DataFrame, we prepare our dataset for effective modeling, ensuring that categorical data is appropriately represented and can be utilized in predictive analytics to improve accuracy and the interpretability of the results. This step is crucial in the preprocessing pipeline, setting the stage for robust model training and evaluation.

The Process - 
![Screenshot 2024-05-08 at 1 00 12 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/0ab0b766-2cd6-42bb-bdb1-4fda97685b54)

The Visual - 
![Screenshot 2024-05-08 at 1 00 20 AM](https://github.com/leandrenash/airlinecustomer/assets/73446394/d0bb51af-e6a8-4291-ac43-8a3aab4f7ddd)


