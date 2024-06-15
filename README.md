# -British-Airways-Predictive-Model
This repository contains a predictive modeling project for British Airways to forecast customer bookings using historical booking data.

## Project Description

The objective of this project is to build a machine learning model to predict the likelihood of a customer completing a booking. The model uses various features such as `purchase_lead`, `flight_hour`, `length_of_stay`, and more to make predictions. The results are used to enhance customer engagement and operational efficiency.

## Dataset

The dataset used for this project is `customer_booking.csv`. It contains various features related to customer bookings.

## Files

- `customer_booking.csv`: The dataset used for the project.
- `notebook.ipynb`: Jupyter notebook with the data exploration, preprocessing, model training, and evaluation steps.
- `feature_importance.png`: Visualization of the top 20 feature importances.
- `presentation.pptx`: PowerPoint presentation summarizing the findings of the project.

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
    ```
2. Navigate to the project directory:
    ```bash
    cd YOUR_REPOSITORY_NAME
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Open the Jupyter notebook:
    ```bash
    jupyter notebook notebook.ipynb
    ```

## Results

- **Accuracy**: 85%
- **ROC AUC Score**: 0.78

## Key Features

- `purchase_lead`: The number of days in advance the booking was made.
- `flight_hour`: The hour of the flight.
- `length_of_stay`: Duration of stay.
- `flight_day`: The day of the week when the flight is scheduled.
- `num_passengers`: Number of passengers in the booking.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
