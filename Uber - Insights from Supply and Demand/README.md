# Insights from City Supply and Demand Data

This project analyzes Uber's city supply and demand data to answer key questions related to trip completion, rider demand, and driver availability over a two-week period. The insights derived from this dataset will help optimize scheduling and improve the balance between supply and demand in a dynamic environment.

## Project Overview

This data project has been used as a take-home assignment during the recruitment process for Data Science positions at Uber. The dataset provides information on the number of ride requests, completed trips, driver supply, and user interactions with the app ("Eyeballs") across different hours and dates.

### Dataset

You must be a yearly or lifetime subscriber to download the dataset.  
**Download Dataset:** [Click here to download](https://github.com/abhishek-sriram/DS-Hands-On/blob/main/Uber%20-%20Insights%20from%20Supply%20and%20Demand/dataset_1.csv)

The dataset is provided in the file `dataset_1.csv` and contains the following columns:

| Column Name        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `Date`             | Date of the record                                                          |
| `Time (Local)`     | Local time of the record (hour of the day)                                  |
| `Eyeballs`         | Number of people who opened the app during that hour                        |
| `Zeroes`           | Number of people who opened the app but did not see a car available         |
| `Completed Trips`  | Number of successful trips completed during the hour                        |
| `Requests`         | Number of ride requests made during the hour                                |
| `Unique Drivers`   | Number of drivers available in the system during the hour                   |

## Assignment

The tasks for this project include answering the following questions:

1. **Most Completed Trips**: Which date had the most completed trips during the two-week period?
2. **Highest Trip Volume**: What was the highest number of completed trips within a 24-hour period?
3. **Busiest Hour**: Which hour of the day had the most requests during the two-week period?
4. **Weekend Zeroes**: What percentage of all "zeroes" occurred on weekends (Friday 5 PM to Sunday 3 AM)?
5. **Weighted Average of Completed Trips per Driver**: What is the weighted average ratio of completed trips per driver during the two-week period?
6. **Busiest Shift**: When are the busiest 8 consecutive hours in terms of unique requests over the two-week period (considering a shift of 8 hours starting every 8 hours)?
7. **Supply vs. Demand**: True or False: Driver supply always increases when demand increases during the two-week period.
8. **Zeroes to Eyeballs Ratio**: In which 72-hour period is the ratio of Zeroes to Eyeballs the highest?
9. **Driver Addition**: If you could add 5 drivers to any single hour of every day during the two-week period, which hour should you choose?
10. **Data Range Check**: True or False: There are exactly two weeks of data in this analysis.
11. **True "End Day"**: Which time might make the most sense to consider a true "end day" instead of midnight (when supply and demand are at their natural minimums)?

## Data Description

Below is an example of a row from the dataset:

| Date       | Time (Local) | Eyeballs | Zeroes | Completed Trips | Requests | Unique Drivers |
|------------|--------------|----------|--------|-----------------|----------|----------------|
| 2012-09-10 | 16           | 11       | 2      | 3               | 4        | 6              |

This means that on **September 10, 2012**, during the hour starting at **4 PM** (16:00):
- **11 people** opened the Uber app (`Eyeballs`).
- **2 of them** did not see any car available (`Zeroes`).
- **4 people** requested a ride (`Requests`).
- **3 trips** were successfully completed (`Completed Trips`).
- **6 drivers** were available in the system (`Unique Drivers`).

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/insights-city-supply-demand.git
   cd insights-city-supply-demand
