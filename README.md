# Energy Requirement Prediction

**Author:** Rahul Prem

## Project Overview

This project aims to predict the energy requirements for a future day based on historical hourly energy consumption data spanning from 2010 to 2018. Accurate energy requirement predictions can help in better energy resource management and planning.

## Data Source

The dataset used in this project can be found [here](https://drive.google.com/file/d/1mm00jiXg8kQ6xZeAUk5qbcR3gRYeV54q/view?usp=sharing).

## Data Description

The dataset contains the following columns:
- `date_and_time`: Timestamp in the format yyyy-mm-dd-hh
- `power_MWH`: Energy consumed in Megawatt Hours (MWH)

## Project Structure

### 1. Data Import and Cleaning
- Importing the data using `pandas`.
- Parsing the `date_and_time` column as datetime objects.
- Removing unnecessary columns.

### 2. Exploratory Data Analysis (EDA)
- Visualizations to understand the data patterns and trends.
- Statistical exploration to quantify insights.

### 3. Issues and Challenges
- Identifying issues in the data that make prediction challenging.
- Addressing data irregularities and missing values.

### 4. Model Development
- Splitting the data into training and testing sets.
- Feature engineering to create meaningful predictors.
- Training different machine learning models.
- Evaluating model performance using appropriate metrics.

### 5. Predictions
- Using the trained model to make predictions on future energy requirements.
- Visualizing the prediction results.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

You can install the required packages using:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/rp097/Energy-Consumption-Predictor.git
  ```

3. Navigate to the project directory:
   ```bash
   cd Energy-Consumption-Predictor
   ```

4. Run the Jupyter notebook:
   ```bash
   jupyter notebook Energy_Requirement_Prediction_Rahul_Prem.ipynb
   ```

## Results
The results section includes:
- Visualizations of the predicted vs actual energy requirements.
- Performance metrics of the predictive model.

## Conclusion
This project demonstrates a systematic approach to predicting energy requirements using historical consumption data. By leveraging statistical analysis and machine learning techniques, we can make informed predictions that assist in energy resource management.

## License
This project is licensed under the MIT License.

## Contact
For any questions or feedback, please contact Rahul Prem at rahulprem90@gmail.com
