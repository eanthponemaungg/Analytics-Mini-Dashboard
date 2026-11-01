# Online Retail Analytics Mini-Dashboard (Updated!)

An interactive Python mini-dashboard using Streamlit and Pandas for retail data tracking, management and dynamic sales visualization with filters.

## Features

* Admin and User login
* Add, update, and delete records
* Filter data by date range and country
* View total sales and quantity by country
* Explore price–quantity and quantity–sales relationships
* Track daily sales and quantity trends

## Tech Stack

*   **Language**: Python
*   **Framework**: Streamlit
*   **Data Analysis**: Pandas
*   **Storage**: Excel

## Requirements

* Python 3.11 or 3.12
* Streamlit
* pandas
* openpyxl
* Excel dataset: `analytics_mini.xlsx`

## Installation

### Setup

1. Install Python 3.11 or 3.12.
2. Make sure Python is added to Windows PATH.
3. Download or clone this repository.
4. Open a terminal in the project folder.
5. Run `python --version` to check your Python installation.
6. Run `python -m pip install streamlit pandas openpyxl`.
7. Place `analytics_mini.xlsx` in the same folder as your Python script.

### Project Structure

```text
online-retail-dashboard/
├── analytics.py
└── analytics_mini.xlsx
```

### Run the Dashboard

1. Run `python -m streamlit run app.py`.
2. Replace `app.py` with your actual Python filename if different.
3. Open the Local URL displayed in the terminal, usually http://localhost:8501.
4. Keep the terminal open while using the dashboard.
5. Press `Ctrl + C` in the terminal to stop the application.

### Demo Accounts

| Role | Username | Password |
|------|----------|----------|
| Admin | Admin | Admin*@123*@ |
| User | User | User*@456*@ |

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
