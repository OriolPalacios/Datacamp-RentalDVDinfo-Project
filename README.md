# DVD Rental Prediction

This project leverages a regression model to predict the number of days a customer will rent a DVD based on various features. The model is designed to achieve a mean squared error (MSE) of 3 or less on the test set, which will aid the company in optimizing inventory planning.

## Project Structure

- **[notebook.ipynb](notebook.ipynb)**: A Jupyter Notebook that documents the analysis, exploratory data analysis (EDA), feature engineering, and the development of regression models.
- **[rental_info.csv](rental_info.csv)**: The dataset containing rental information. The key features include:
  - `"rental_date"`: The date and time when the customer rents the DVD.
  - `"return_date"`: The date and time when the customer returns the DVD.
  - `"amount"`: The amount paid by the customer.
  - `"amount_2"`: The square of the `"amount"`.
  - `"rental_rate"`: The rate at which the DVD is rented.
  - ... *(more features can be detailed as needed from the CSV)*

## Overview

A DVD rental company needs help predicting how many days a customer will keep a DVD rented. The goal is to build and evaluate different regression models to meet or beat an MSE of 3 on unseen data. The notebook contains the following:

- **Data Visualization**: Examine relationships between features.
- **Feature Engineering**: Create and transform variables to improve model performance.
- **Model Training and Evaluation**: Experiment with various regression techniques to find the most effective predictor.

## Getting Started

1. **Clone the Repository:**
   ```sh
   git clone <repository-url>
   cd <repository-folder>
   ```
2. **Setup Environment**: Make sure you have Jupyter Notebook installed

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request on the repository.

## License
This project is licensed under the MIT License

