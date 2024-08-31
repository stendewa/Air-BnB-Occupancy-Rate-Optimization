# Air-BnB-Occupancy-Rate-Optimization
This is a self initiated project to get the best Air BnB occupancy rate for the Western Cape Region of South Africa.

## Buisness Understanding
Milkah Petso is a young enterprenuer who seeks to venture into the Air BnB buisness model in the Western part of Cape Town. She has asked me to find find the optimum property
in the optimum neighborhood within the given region to maximize her ocupancy so she can rent one within the area and furnish it to start her Air BnB buiseness.

## Buisness Questions
Below are the buisness questions we need to answer;
1. What factors affect occupancy rate the most in an Air BnB listing?
2. What can be done to increase the positive effects of these factors?
3. What is the best performing neighbourhood on the Western Cape in terms of occupancy rate?

## Data Understanding


### Source
The data will be sourced from the (Inside AirBnB platform )[https://insideairbnb.com/get-the-data/]. Generally quarterly data for the last 12 months.

### Description
The data contains the following columns as decsribed;

1. id - The guest id
2. name - the name of the guest
3. host_id - the host's id
4. host_name - The host's name
5. neighbourhood_group - the grouped neighboodhood
3. neighbourhood - the specific neighbourhood
6. latitude - The latitude
7. longitude - the longitude
8. room_type - the type of room
9. price - the price per night
10. minimum_nights - minimum number of nights per stay
11. number of reviews - number of reviews
12. last review - last review
13. reviews  per month - reviews per month
15. calculated host listings_count - The number of listings the host has in the city/region
17. availability_365 - the number of days the listing is available per year
18. number of reviews ltm - reviews recieved in the last twelve months
19. license - license or registration number required by local authorities for short-term rental properties

## Data Cleaning and Feature Engineering
The data was cleaned by dropping NaN values, imputing missing numerical values, dropping irrelevant columns and leaving the neighbourhood, number of reviews, minimum_nights and room type.
I one hot encoded the categorical variables i.e room type and neighbourhood.

## Models used
1. Decision Tree Classifier
2. Logistic Regression
3. Random Forest Classifier

### Decision Tree Classifier
The model performed well and with a clssification table determined an accuracy of 1.0

### Logistic Regression
The model did well on both the training and test data and determined an accuracy test with 99% for both

### Random Forest Classifier
The model performed well on the training and test data and determined an accuracy of 99% using a cross validation test
