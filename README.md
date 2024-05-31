# Stock Price Prediction 
This project aims to analyze stock market data and predict stock prices using various machine learning models. The analysis focuses on three major sectors from the HOSE stock exchange: Materials, Utilities, and Industrials. The selected stocks are:
- **Materials:** HPG (Hoa Phat Group GSC)
- **Utilities:** GAS (Petro VietNam Gas JS)
- **Industrials:** CTG (Viet Nam Joint Stock Commercial Bank for Industry and Trade)

The project also examines the impact of macroeconomic factors and political events on stock prices, providing insights into broader economic trends and their influence on the stock market.
## Project Structure

### 1. "Data analysis and feature selection" folder
- **File:** `data_analysis_and_feature_selection.ipynb`
- **Description:** This Jupyter Notebook includes the process of selecting the right stock codes and analyzing the relationship between macroeconomic factors, political events, and stock market performance. The analysis covers significant events such as the 2008-2009 Financial Crisis, the period of stability from 2012-2015, fluctuations due to political changes and trade tensions from 2016-2020, and the impact of the COVID-19 pandemic from 2020-2022.

### 2. "Data" folder 
- **processed:** Contains cleaned and processed datasets.
- **raw:** Contains raw datasets before any preprocessing.

### 3. "Members" folder
- **Description:** Contains subfolders for each team member, each implementing a different stock price prediction model.
  - **"AVu" Folder:**
    - `SVR Stock.ipynb` contains SVR model.
  - **"KTrinh" Folder:**
    - `xgboost.ipynb` containsXGBoost model.
  - **"MCuong" Folder:**
    - `AdaBoost.ipynb` contains AdaBoost model.
  - **"TDung" Folder:**
    - `LinearRidges.ipynb` contains LinearRidges model.
  - **"TPhong" Folder:**
    - `RandomForest.ipynb` contains RandomForest model.
  - **"VLong" Folder:** Contains ARIMA models for CTG, GAS, and HPG stocks.
    - `arima_ctg.ipynb`: ARIMA model for CTG stock.
    - `arima_gas.ipynb`: ARIMA model for GAS stock.
    - `arima_hpg.ipynb`: ARIMA model for HPG stock.

### 4. "Model Evaluation" folder
- Contains evaluation results for all models, including test set results and train set results.
  - **`Test set results.png`** Summaries of model performance on train set with different metrics.
  - **`Train set results.png`** Summaries of model performance on test set with different metrics.
### 5. requirements.txt
-  Lists all the packages and dependencies required to run the project.
### 6. Report folder
### 7. Slide folder
## Instructions

1. **Data Analysis and Feature Selection:**
   - Open `data_analysis_and_feature_selection.ipynb` in Jupyter Notebook.
   - Follow the steps to understand the data selection and feature extraction process.

2. **Model Implementation:**
   - Navigate to the `Members` folder.
   - Open the respective subfolder for each model to understand the implementation details.
   - Run the notebooks to see the predictions made by each model.

3. **Model Evaluation:**
   - Open the `Model Evaluation` folder to review the performance metrics of each model.

4. **Dependencies:**
   - Install the required packages using the `requirements.txt` file.
   ```bash
   pip install -r requirements.txt

