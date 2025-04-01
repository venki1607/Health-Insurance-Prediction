# Health Insurance Cost Predictor

## Overview
This project is a **Health Insurance Cost Predictor** built using Streamlit. It allows users to input various personal and health-related details to predict their estimated health insurance cost. The model leverages machine learning techniques to make predictions based on input parameters.

## Features
- User-friendly Streamlit interface.
- Predicts health insurance costs based on personal and medical details.
- Uses machine learning models trained on relevant datasets.
- Handles categorical and numerical inputs efficiently.

## Technologies Used
- **Python**
- **Streamlit** for UI
- **Pandas** for data manipulation
- **Joblib** for model loading
- **Scikit-learn** for preprocessing and modeling

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/health-insurance-predictor.git
   cd health-insurance-predictor
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run main.py
   ```

## Usage
1. Enter the required details such as Age, Income, BMI, Smoking Status, etc.
2. Click on the **Predict** button.
3. The predicted health insurance cost will be displayed.

## Project Structure
```
health-insurance-predictor/
│── main.py                # Streamlit UI for prediction
│── prediction_helper.py   # Helper functions for predictions
│── artifacts/             # Pre-trained models
│── requirements.txt       # Required dependencies
│── README.md              # Project documentation
```

## Model Details
The project utilizes two different machine learning models:
- **model_young.joblib**: For individuals aged 25 or younger.
- **model_rest.joblib**: For individuals above 25.

The input features are scaled using pre-fitted scalers:
- **scaler_young.joblib**: Scaling for younger individuals.
- **scaler_rest.joblib**: Scaling for older individuals.

## Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push the changes and submit a pull request.

## License
Venkatesh Surabathula
codebasics.io


