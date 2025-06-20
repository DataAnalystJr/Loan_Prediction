# Loan Approval Prediction Application

This is a Streamlit-based web application that predicts whether a loan applicant is likely to repay their loan based on various factors such as income, credit history, education, and other relevant parameters.

## Features

- Interactive web interface for loan application input
- Real-time loan approval prediction
- Visual representation of prediction probabilities
- Support for various input parameters including:
  - Personal information (gender, marital status, dependents)
  - Financial information (income, loan amount, loan term)
  - Credit history and property details
  - Education and employment status

## System Requirements

- Python 3.8 or higher
- Windows operating system (for the batch file)
- Internet connection (for first-time package installation)
- **(Optional)** Microsoft Visual C++ Build Tools (only required if a package needs to be built from source; most users do not need this if using a supported Python version and up-to-date pip)

**Tip:** Before installing requirements, it is recommended to upgrade pip, setuptools, and wheel:
```
python -m pip install --upgrade pip setuptools wheel
```

## Installation

1. Create a virtual environment (recommended):
   ```
   python -m venv venv
   venv\Scripts\activate
   ```

2. **Navigate to the project directory (where requirements.txt is located):**
   ```
   cd path/to/Loan_Prediction
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

### Method 1: Using the Batch File (Windows)
Simply double-click the `run_loan_app.bat` file in the application directory.

### Method 2: Using Command Line
1. Open a terminal in the application directory
2. Run the following command:
   ```
   streamlit run streamlit_app.py
   ```
### Method 3: go to swiftcapitalcda.streamlit.app
1. If the app is asleep as stated when accessing the website, click the "Yes, get this app back up!"
2. Wait for it to load and the website will load fully.


## Usage

1. Fill in all the required fields in the application form
2. Click the "Submit" button to get the prediction
3. View the prediction results and probability visualization
4. Use the "Clear" button to reset the form for a new prediction

## Model Information

The application uses a Random Forest model trained on historical loan data. The model considers various features to make predictions about loan repayment probability.

## Support

If you encounter any issues or have questions, please check the following:
1. Ensure all required packages are installed correctly
2. Verify that Python 3.8 or higher is installed
3. Check that all files are in their correct locations

## License

This project is licensed under the terms included in the LICENSE file. 