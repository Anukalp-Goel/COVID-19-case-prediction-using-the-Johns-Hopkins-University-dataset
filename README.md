# README: COVID-19 Case Projections and Analysis

## Overview
This project analyzes the spread of COVID-19 using data from the COVID-19 Data Repository by Johns Hopkins University. The goal is to develop models that project future COVID-19 case counts, considering best, worst, and base-case scenarios. The project also explores correlations between COVID-19 cases and another dataset of your choice, providing evidence-based insights to help guide policymakers in mitigating the pandemic's effects.

## Files
- `code.ipynb`: The main Jupyter Notebook containing the implementation of the analysis.
- `time_series_covid19_confirmed_US.csv` or `time_series_covid19_confirmed_global.csv`: The datasets used to model COVID-19 case numbers.
  
## Project Components

### 1. Data Cleaning
The data cleaning pipeline focuses on preparing time-series data by:
- Extracting COVID-19 case counts for a selected location (e.g., state, province, country).
- Cleaning cumulative case count data to format it appropriately for time-series modeling.

### 2. Data Visualization and Exploratory Analysis
The data was explored through visualizations, including time-series graphs that track the progression of case counts. These visualizations provided insights into trends and guided the selection of models for forecasting.

### 3. Model Selection and Fitting
A machine learning or data science model (such as ARIMA, SIR, or Monte Carlo simulation) was selected to forecast COVID-19 cases. Three scenarios were modeled:
- **Worst Case**: Maximum spread with minimal interventions.
- **Best Case**: Minimal spread due to strong interventions.
- **Base Case**: A moderate projection between the worst and best cases.

### 4. Correlating COVID-19 Projections to a Secondary Dataset
A secondary dataset was used to study a factor related to COVID-19 cases, such as mask mandates, social distancing policies, or economic impacts. The analysis explored how these factors influenced the progression of COVID-19 in the selected location.

### 5. Policy and Guidance Insights
Based on the model projections, evidence-based insights were derived. The project offers recommendations for public health interventions, policies, or actions that governments and health officials can use to combat the pandemic.

## Results
The model results provide forecasts for COVID-19 case counts under different scenarios. Additionally, correlations with the secondary dataset offer actionable insights for mitigating the pandemic's effects in the selected location.

## Future Improvements
- Incorporating more advanced models (e.g., deep learning) to improve forecast accuracy.
- Using more granular datasets for better local-level analysis.

## Instructions to Run the Project
1. Install the necessary Python libraries (e.g., `Numpy`, `Pandas`, `Matplotlib`, `Scikit-learn`).
2. Open `code.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells sequentially to execute the analysis and generate the forecasts.

## License
This project is for academic purposes related to the MIE 1624 course at the University of Toronto.
