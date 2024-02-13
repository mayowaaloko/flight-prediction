
---

# Flight Booking Prediction

## Introduction

The objective of this project is to analyze a flight booking dataset obtained from the "Ease My Trip" website. We will conduct various statistical hypothesis tests and use the 'Linear Regression' algorithm to predict a continuous target variable. "Easemytrip" is an internet platform for booking flight tickets, and understanding this data will provide valuable insights for potential passengers.

## Research Questions

We aim to answer the following research questions:
1. **Does price vary with Airlines?**
2. **How does the price change when tickets are bought just 1 or 2 days before departure?**
3. **Does ticket price depend on departure and arrival times?**
4. **How does the price change based on the source and destination?**
5. **What is the variation in ticket price between Economy and Business class?**

## Data Collection and Methodology

- We used the **Octoparse** scraping tool to extract data from the "Ease My Trip" website.
- Data was collected in two parts: one for economy class tickets and another for business class tickets.
- A total of **300,261 distinct flight booking options** were extracted from the site.
- Data was collected over **50 days**, from **February 11th to March 31st, 2022**.
- The data source was secondary data obtained from the Ease My Trip website.

## Dataset

The dataset contains information about flight booking options for travel between India's top 6 metro cities. It includes **11 features** and **300,261 datapoints**.

---

## Dataset Features

1. **Airline**: Categorical feature representing the airline company (6 different airlines).
2. **Flight**: Categorical feature storing information about the plane's flight code.
3. **Source City**: Categorical feature indicating the departure city (6 unique cities).
4. **Departure Time**: Derived categorical feature based on time periods (6 unique time labels).
5. **Stops**: Categorical feature with 3 distinct values (number of stops between source and destination).
6. **Arrival Time**: Derived categorical feature based on time intervals (6 distinct time labels).
7. **Destination City**: Categorical feature representing the arrival city (6 unique cities).
8. **Class**: Categorical feature with two values: Business and Economy (seat class).
9. **Duration**: Continuous feature indicating the total travel time between cities (in hours).
10. **Days Left**: Derived characteristic calculated by subtracting the trip date from the booking date.
11. **Price**: Target variable storing ticket prices.

## Methodology

1. **Data Collection**: Scraped data from the "Ease My Trip" website using Octoparse.
2. **Statistical Analysis**: Conducted hypothesis tests and explored relationships between features.
3. **Machine Learning**: Utilized linear regression for price prediction.
4. **Insights**: Extracted valuable insights for passengers and airlines.

## Project Goals

- Predict ticket prices based on historical data.
- Understand how different factors impact flight prices.
- Optimize booking strategies for passengers.

## Repository Contents

- `Flight Prediction.ipynb`: Jupyter notebook with data exploration, statistical tests, and machine learning models.
- `README.md`: Overview of the project (you're reading it now!).

Feel free to explore and contribute to this project! 🛫✈️

---
