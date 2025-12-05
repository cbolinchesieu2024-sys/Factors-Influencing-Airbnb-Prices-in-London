README

1. Factors Influencing Airbnb Prices in London

This project analyzes which factors influence Airbnb listing prices in London. The analysis focuses on how location, room type, host characteristics, and property attributes relate to listed prices. The goal is to understand pricing patterns and identify which features have the strongest impact on Airbnb costs across the city.

2. Dataset

The dataset used in this project comes from the Inside Airbnb open-data platform. It is not included in this repository due to file size limitations.
It can be downloaded from the following link:

Dataset link:(https://data.insideairbnb.com/united-states/ny/albany/2025-10-05/data/listings.csv.gz)

Place the dataset in the project folder before running the notebook.

3. Project Objectives

The notebook includes the following steps:

- Loading and inspecting the dataset

- Cleaning and converting key variables (such as the price column)

- Handling missing values

- Exploring distributions and correlations

- Creating visualizations for price patterns

- Interpreting results and drawing conclusions

4. Key Findings

Based on the analysis:

- Location is one of the strongest factors affecting Airbnb prices in London. Listings in central boroughs such as Westminster and Kensington & Chelsea are significantly more expensive.

- Room type is another major influence. Entire homes and hotel rooms tend to have much higher prices, while private rooms and shared spaces are generally more affordable.

- The number of guests a listing can accommodate has a mild positive correlation with price, although the relationship is weakened by outliers and variation in property types.
  
- Host status (such as being a superhost) does not significantly increase prices. Prices between regular hosts and superhosts are similar.

- Overall, the most important variables appear to be neighbourhood and room type, rather than host characteristics.

5. Limitations

- Several limitations should be considered:

- The dataset represents a single point in time and does not reflect seasonal changes or long-term pricing trends.

- Price does not necessarily represent booked price or revenue; it only reflects the listed nightly rate.

- The data may include outliers that affect averages and correlations.

- The analysis is observational and cannot determine the exact causes behind pricing differences.

6. Potential Improvements

- Future extensions of this project could include:

- Using revenue or availability data to understand financial performance more accurately.

- Combining multiple datasets to include neighbourhood-level socioeconomic factors.

- Training a predictive model (such as linear regression) to estimate prices based on listing features.

- Performing additional data cleaning, such as handling outliers in a more systematic way.

- Comparing London results with another city to determine whether pricing patterns generalize.

7. Tools and Libraries

- Python

- Jupyter Notebook

- Pandas, NumPy

- Matplotlib, Seaborn

- Additional libraries as needed

8. How to Run the Project

  1.Download the dataset from the link above.

  2.Place it in the same directory as the notebook.

  3.Open the notebook in Jupyter or a compatible environment.

  4.Run all cells in order.
 
  5.Ensure all required Python libraries are installed.





