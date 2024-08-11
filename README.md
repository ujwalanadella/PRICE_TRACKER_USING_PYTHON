# Price Tracker using Python

Welcome to the Price Tracker project! This application is designed to monitor the prices of products across various e-commerce websites. It alerts users when prices drop, helping them make informed purchasing decisions.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Product Monitoring**: Track the price of specified products on various e-commerce platforms.
- **Price Alerts**: Receive notifications when the price drops below a specified threshold.
- **Data Logging**: Store historical price data for analysis.
- **User-Friendly Interface**: Simple command-line interface to add products and view alerts.

## Technologies Used

This project utilizes the following technologies:

- **Python**: Programming language used for implementation.
- **Beautiful Soup**: For web scraping and parsing HTML data.
- **Requests**: For making HTTP requests to retrieve product data.
- **Pandas**: For data manipulation and analysis.
- **SQLite**: For storing product data and user preferences.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ujwalanadella/PRICE_TRACKER_USING_PYTHON.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd PRICE_TRACKER_USING_PYTHON
   ```

3. **Install required libraries**:
   It’s recommended to create a virtual environment and install the dependencies. You can do this with the following commands:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   pip install -r requirements.txt
   ```

## Usage

After installing the required libraries, you can start using the application by following these steps:

1. **Run the price tracker script**:
   Execute the following command to start monitoring prices:
   ```bash
   python price_tracker.py
   ```

2. **Add products to track**:
   Follow the prompts to enter the URL of the product you want to track and the desired price threshold.

3. **Check for price alerts**:
   The script will periodically check the prices of the tracked products and notify you if the price drops below your specified threshold.

4. **View historical data**:
   You can also view historical price data logged during the monitoring process.

## Project Structure

Here’s a brief overview of the project structure:

```
PRICE_TRACKER_USING_PYTHON/
│
├── data/                   # Directory for storing historical data (optional)
│   └── prices.db           # SQLite database for product price tracking
│
├── src/                    # Source code for the application
│   ├── price_tracker.py     # Main script to run the price tracker
│   ├── scraper.py           # Script for web scraping product prices
│   └── notifier.py          # Script for sending notifications
│
├── requirements.txt        # Required Python packages
└── README.md               # Project documentation
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b feature/YourFeature`).
3. **Make your changes** and commit them (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/YourFeature`).
5. **Open a pull request**.

