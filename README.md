# Hotel Booking Cancellation Prediction

This project focuses on analyzing hotel booking data to understand cancellation patterns and build predictive models to determine whether a booking is likely to be canceled. Predicting cancellations helps hotels optimize revenue management, manage overbooking strategies, and improve overall operational efficiency.

## Project Overview

The analysis follows a comprehensive machine learning pipeline, starting from raw data exploration to model evaluation.

* **Exploratory Data Analysis (EDA):** Visualizing distributions of cancellations across different variables such as hotel types (City vs. Resort), arrival months, and market segments.
* **Data Preprocessing:** * Handling missing values in features like `children`, `country`, and `agent`.
    * Encoding categorical variables (e.g., `meal`, `distribution_channel`, `room_type`) into a format suitable for machine learning models.
    * Feature scaling using standard techniques to ensure model stability.
* **Predictive Modeling:** Implementing and comparing various classification algorithms, including:
    * Logistic Regression
    * Random Forest Classifier
* **Performance Evaluation:** Assessing models based on accuracy, precision, recall, and F1-score to identify the most reliable predictor.

## Technologies Used

* **Python**: The primary programming language.
* **Pandas & NumPy**: For data manipulation and numerical analysis.
* **Matplotlib & Seaborn**: For data visualization and EDA.
* **Scikit-Learn**: For preprocessing, feature scaling, and implementing machine learning algorithms.

## Dataset

The project utilizes a `hotel_bookings.csv` dataset containing various booking attributes such as lead time, stay duration, number of guests, and booking channel.

## Getting Started

1.  Clone this repository.
2.  Ensure you have the required dependencies installed:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Open `Hotel_booking_Management.ipynb` in a Jupyter environment or Google Colab.
4.  Run the cells to see the analysis, visualizations, and model performance.
