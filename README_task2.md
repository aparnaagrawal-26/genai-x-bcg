# Financial Chatbot - Task 2 Submission 2

## Overview

This project is a Flask-based web application that functions as a financial chatbot. It allows users to query financial data for specific companies and years, providing responses based on the data stored in a CSV file. The application is designed to be user-friendly and provides insights into various financial metrics.

## Features

- **Query Financial Data**: Users can ask questions about various financial metrics such as total revenue, net income, total assets, total liabilities, operating expenses, and cash flow.
- **Dynamic Responses**: The application generates responses based on the user's input for company and year, providing formatted strings with the relevant financial metrics.
- **User-Friendly Interface**: The web interface is designed to be intuitive and easy to use, allowing users to input their queries and receive responses quickly.

## Components

- **Flask Application (`app.py`)**: The main application file that handles routing and data processing. It defines routes for rendering the main page and processing user queries.
- **Static Files**:
  - `script.js`: Client-side JavaScript for handling user interactions and making API calls to the Flask backend.
  - `styles.css`: CSS styles for the web application, ensuring a user-friendly interface.
- **Templates**:
  - `index.html`: The main HTML template for the web application, where users can input their queries.
- **Data Source**:
  - `financial_data.csv`: Contains the financial data used for querying, including metrics such as total revenue, net income, total assets, total liabilities, operating expenses, and cash flow.

## How to Run

1. **Install Dependencies**:
   Ensure you have Python and Flask installed. You can install Flask using pip:
   ```bash
   pip install Flask
   ```

2. **Run the Application**:
   Navigate to the project directory and run the Flask application:
   ```bash
   python app.py
   ```

3. **Access the Application**:
   Open your web browser and go to `http://127.0.0.1:5000/` to access the financial chatbot.

## Documentation

For more detailed information about the project, refer to the `Financial_Chatbot_Documentation.pdf` file included in the project directory. This document provides insights into the project's setup, usage, and any additional features.

## Future Improvements

- **Error Handling**: Implement robust error handling for data processing to manage potential issues like missing values or incorrect data types.
- **Modularize Code**: Break down the code into functions for data loading, processing, and visualization to improve maintainability.
- **Interactive Visualizations**: Consider using interactive visualization libraries like Plotly to create more engaging and interactive plots.
- **Data Validation**: Implement data validation checks to ensure the integrity of the data before performing analysis.
- **Performance Optimization**: If the dataset is large, consider optimizing the code for performance, such as using vectorized operations in pandas.

## Conclusion

This project demonstrates the use of Flask to create a financial chatbot that provides valuable insights into financial data. It is a great example of how web applications can be used to interact with and analyze financial information effectively. 
