# Spotify Songs Analysis

This project aims to analyze a dataset containing information about songs streamed on Spotify in 2021. The dataset includes various attributes such as artist, genre, duration, popularity, and more. The analysis involves data cleaning, exploratory data analysis, implementing queries using both SparkSQL and SparkDataframes, and finally, performing classification to predict song genres using SparkML.

## Dataset

The dataset used for this project contains information about songs streamed on Spotify in 2021. It includes attributes like artist, genre, duration, popularity, and more. Prior to analysis, data cleaning and preprocessing steps are performed to ensure data quality and usability.

## Queries Implemented

### 1. Genre Analysis
a) Identify the genre with the highest average popularity.
b) Determine the artist who has recorded the most number of songs with a duration of more than 5 minutes.
c) Count the number of songs included in each genre.
d) Identify the artists who dominated the charts.

### 2. Song Recommendations
e) Recommend at least 5 fun/not-boring songs that can be played at a party. Features like energy, danceability, etc., will be considered to represent cheerfulness.

## Implementation Details

1. **Data Cleaning & Engineering**: This phase involves handling missing values, duplicates, and any necessary data transformations to render the data usable for analysis.

2. **Queries Implementation**: The queries mentioned above are be implemented twice, once using SparkSQL and then using SparkDataframes. This approach allows for comparing the efficiency and usability of both methods.

3. **Classification**: The dataset is split into training and testing sets. Classification tasks are performed using SparkML to predict the genre of each song. Three different classification methods (Logistic Regression, Random Forest, and Decision Tree) are applied, and their accuracies are compared to determine the best classifier.

## How to Use

To replicate the analysis or explore the dataset further, follow these steps:

1. Clone the repository.
2. Download the dataset and place it in the designated directory.
3. Run the provided scripts or notebooks for data cleaning, queries implementation, and classification.
4. Explore the results and analysis provided in the output.

## Conclusion

This project offers insights into the streaming patterns of songs on Spotify in 2021. By implementing various queries and classification tasks, we aim to understand the trends in music genres, artist popularity, and provide recommendations for enjoyable party songs. The comparison of SparkSQL and SparkDataframes for query implementation, along with evaluating different classification methods, provides valuable insights for data analysis in Spark environments.
