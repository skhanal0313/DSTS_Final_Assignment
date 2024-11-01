
# Flight_Delay_Prediction_ML_Model

## Problem: Predicting Airplane Delays

This project aims to predict flight delays due to weather conditions. By leveraging machine learning, we aim to enhance customer experience by informing travelers of potential delays during the booking process.

## Project Goals

The primary objectives of this project are:

- Process and compile a dataset from compressed monthly files
- Perform exploratory data analysis (EDA) on flight data
- Build a baseline model to predict flight delays and work to improve its accuracy

---

## Business Scenario

A travel booking website seeks to improve customer experience by providing real-time information about potential delays due to weather for flights to and from the busiest US domestic airports. The company’s goal is to help customers make informed travel decisions by notifying them of any expected delays at the time of booking. Our task involves developing a machine learning model to identify flights that are likely to be delayed due to adverse weather conditions.

## Dataset Overview

The dataset consists of records on the on-time performance of domestic flights operated by major US air carriers, accounting for at least 1% of domestic scheduled passenger revenue. The dataset includes detailed flight information, including scheduled and actual departure/arrival times, origin, destination, airline, distance, and delay status.

- **Source:** Office of Airline Information, Bureau of Transportation Statistics (BTS)
- **Data Range:** 2014-2018
- **File Format:** Monthly CSV files, compressed into 60 files, each covering one month across five years
- **Data Download Link:** [Data Source](https://ucstaff-my.sharepoint.com/:f:/g/personal/ibrahim_radwan_canberra_edu_au/Er0nVreXmihEmtMz5qC5kVIB81-ugSusExPYdcyQTglfLg?e=bNO312)
- **Bureau of Transportation Statistics Data:** [BTS Airline On-Time Performance Data](https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ)

To start, download the data and ensure all files are saved in a relative path as specified in the setup instructions.

## Steps Involved

1. **Data Processing**: Load and preprocess data from the provided ZIP files to create a structured dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Conduct EDA to understand patterns and correlations in the data, particularly those related to delays and weather conditions.
3. **Model Development**: Develop a baseline machine learning model to classify flights by delay status and iteratively improve model performance.

## Technical Requirements

- Python 3.x
- Required Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Flight_Delay_Prediction_ML_Model.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Flight_Delay_Prediction_ML_Model
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

- Run the preprocessing script to compile data into a single, clean dataset.
- Execute the notebook to perform EDA and build machine learning models.
- Review model performance metrics and make adjustments as needed.

## Contributors

- [Sujan Khanal](https://github.com/skhanal0313)
