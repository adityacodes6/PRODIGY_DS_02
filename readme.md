# ✈️ Airline Passenger Satisfaction Analysis – EDA

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an airline passenger satisfaction dataset. The main objective is to understand passenger behaviour, analyze airline service ratings, investigate flight delays, and identify patterns and relationships that may influence passenger satisfaction.

The project uses Python and its data analysis and visualization libraries to clean, explore and interpret the dataset.

## Objectives

- Understand and explore airline passenger data.
- Perform data cleaning and handle missing values.
- Analyze passenger satisfaction levels.
- Study passenger age, travel class and travel type distributions.
- Investigate departure and arrival delays.
- Identify the most and least satisfactory airline services.
- Explore relationships between passenger categories and satisfaction.
- Identify patterns, trends and meaningful business insights.

## Dataset

**Dataset:** Airline Passenger Satisfaction

**Source:** [Kaggle – Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

The dataset contains passenger information, travel details, airline service ratings, flight distances, delays and satisfaction levels.

### Important Features

| Feature | Description |
|---|---|
| Gender | Passenger gender |
| Customer Type | Type of customer |
| Age | Passenger age |
| Type of Travel | Business or personal travel |
| Class | Travel class |
| Flight Distance | Distance travelled |
| Departure Delay in Minutes | Departure delay duration |
| Arrival Delay in Minutes | Arrival delay duration |
| Satisfaction | Passenger satisfaction status |

The dataset also includes several airline service ratings, such as inflight Wi-Fi, seat comfort, online boarding, food and drink, baggage handling and cleanliness.

## Technologies and Libraries Used

- **Python** – Programming language
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis environment

## Project Workflow

### 1. Data Loading and Understanding

- Imported the required Python libraries.
- Loaded the training and testing CSV files.
- Inspected the dataset using initial records and dataset dimensions.
- Examined column names and data types.
- Generated descriptive statistics.

### 2. Data Cleaning

- Identified missing values.
- Handled missing values in the arrival delay column using mean imputation.
- Checked duplicate records.
- Inspected unnecessary index columns.
- Verified the dataset after cleaning.

### 3. Exploratory Data Analysis

Performed different types of analysis to understand the dataset.

**Passenger Analysis**
- Passenger satisfaction distribution.
- Passenger age distribution.
- Customer class distribution.
- Travel type distribution.

**Flight Distance and Delay Analysis**
- Flight distance distribution.
- Departure delay distribution.
- Arrival delay distribution.
- Comparison of departure and arrival delays.
- Identification of unusual delay values using box plots.

### 4. Pattern and Trend Identification

- Identified passenger groups with higher satisfaction rates.
- Compared airline service ratings.
- Identified services with lower average ratings.
- Analyzed departure delay categories.
- Explored the relationship between flight delays and satisfaction.
- Compared satisfaction across different passenger categories.
- Examined correlations among numerical variables.

### 5. Data Visualization

The project uses different visualization techniques:

- Bar charts
- Count plots
- Histograms
- Box plots
- Scatter plots
- Correlation heatmaps

## Key Business Questions

The analysis aims to answer the following questions:

1. Which passenger groups have the highest satisfaction rates?
2. Which airline services receive the lowest average ratings?
3. What are the common patterns in flight delays?
4. How does satisfaction differ across customer classes and travel types?
5. Are departure delays associated with arrival delays?
6. Which numerical variables have the strongest correlations?
7. Which airline services could benefit from improvement?

## How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-link>
```

### 2. Navigate to the project directory

```bash
cd Airline_Flight_Analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open `airline_flight_analysis.ipynb` and execute the cells in sequence.

Ensure the required dataset CSV files are available in the appropriate project directory.

## Project Structure

```text
Airline_Flight_Analysis/
│
├── dataset/
│   ├── train.csv
│   └── test.csv
│
├── airline_flight_analysis.ipynb
│
└── README.md
```

## Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand airline passenger behaviour and satisfaction.

Through data cleaning, statistical analysis and visualization, the project explores passenger demographics, travel preferences, airline service ratings and flight delays.

The findings can help identify areas where airlines may improve their services and enhance the overall passenger experience.

## Author

**Aditya Mungekar**

B.Sc. Data Science and Analytics

**Project Type:** Exploratory Data Analysis (EDA)