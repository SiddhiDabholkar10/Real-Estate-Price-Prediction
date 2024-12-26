
# Real Estate Price Prediction

This project aims to predict real estate prices in a locality using machine learning algorithms. The prediction model is built using historical data and various features that influence property prices.

## Table of Contents
- Project Description
- Installation
- Usage
- Project Structure
- Algorithms Used
- Data Sources
- Contributors
- License

## Project Description
The goal of this project is to predict the prices of real estate properties based on various features such as location, size, number of bedrooms, and bathrooms. The project utilizes machine learning models to provide accurate price predictions, which can be useful for buyers, sellers, and real estate professionals.

## Installation
To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/SiddhiDabholkar10/Real-Estate-Price-Prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Real-Estate-Price-Prediction
   ```

3. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Follow the steps below to use the project:

1. Start the Flask server:
   ```bash
   python server/server.py
   ```

2. Open `client/index.html` in your web browser.

3. Enter details such as total square feet, number of bedrooms, number of bathrooms, and location to get the estimated price.

## Project Structure
The project directory structure is as follows:
```
Real-Estate-Price-Prediction/
│
├── client/
│   ├── app.js                 # JavaScript code for client-side logic
│   ├── index.html             # HTML file for the frontend
│   └── style.css              # CSS file for styling
│
├── model/
│   ├── Bengaluru_House_Data.csv # Dataset used for training the model
│   ├── TE_Project.pickle        # Pickle file for the trained model
│   └── TE_PROJECT.ipynb         # Jupyter notebook for model training
│
├── server/
│   ├── server.py              # Flask server code
│   ├── util.py                # Utility functions for data processing
│   ├── factors/
│   │   ├── columns.json        # JSON file with data column names
│   │   └── TE_Project.pickle   # Pickle file for the trained model
│   └── __pycache__/           # Compiled Python files
│
├── README.md                  # Project documentation
└── requirements.txt           # List of dependencies
```

## Algorithms Used
The project uses the following machine learning algorithms:
- Linear Regression: Used for predicting the property prices based on the features.

## Data Sources
The dataset used for this project is `Bengaluru_House_Data.csv`, which contains information about various properties in Bangalore, including features like area type, availability, location, size, society, total square feet, number of bathrooms, balconies, and price.

## Contributors
- Siddhi Dabholkar (GitHub: [SiddhiDabholkar10](https://github.com/SiddhiDabholkar10))

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

Feel free to reach out if you have any questions or suggestions. Enjoy predicting real estate prices!
```
