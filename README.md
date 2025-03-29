# IMPACTX - Machine Learning Project

## Project Overview
This is a machine learning project focused on data analysis and prediction. The project follows a structured approach with tasks divided into respective Jupyter Notebooks, making it easy to follow and execute. The goal is to analyze data, explore patterns, and build predictive models using advanced machine learning techniques.

## Dataset Used
- **Dataset Name**: `Price_Agriculture_commodities_Week`
- **Dataset Link**: `https://www.kaggle.com/datasets/anshtanwar/current-daily-price-of-various-commodities-india`
- **Description**: This dataset contains multiple features related to commodity prices across different regions. It includes variables such as:
  - `Min Price`
  - `Max Price`
  - `Modal Price`
  - `StateDistrictMarket`
  - `Commodity`
  - `Variety`
  - `Grade`
- **Purpose**: Used for exploratory data analysis and model training.

## Tools & Technologies Implemented
- **Programming Language**: Python
- **Libraries Used**:
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization
  - `scikit-learn` for machine learning algorithms
  - `numpy` for numerical computations

## Project Structure
- `00_data_preprocessing.py`- Standardizes raw data and converts catagorical variables into encoded format.
- `01_Data_Analysis.ipynb` - Loads and Performs data exploration, visualizations, and statistical analysis.
- `02_Feature_Engineering.ipynb` - Prepares features for model training.
- `03_Model_Training.ipynb` - Implements machine learning models for predictions and Evaluates model performance using metrics.

## Installation & Setup
To run this project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/impactx.git
   cd impactx
   ```

2. **Create a Virtual Environment (Optional but Recommended)**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebooks**:
   ```bash
   jupyter notebook
   ```
   Then, open and run the notebooks sequentially.

## Execution Instructions
-Can start directly working with the preprocessed data.
1. Open Jupyter Notebook.
2. Start with `01_Data_analysis.ipynb` and execute each cell.
3. Proceed to the next notebook in sequence.
4. Ensure that `preprocessed_data.csv` is available in the project directory.

## Results & Insights
- **Data Visualization**: Histograms, scatter plots, and box plots to analyze feature distributions.
  
- **Correlation Analysis**: Identifies relationships between numerical variables.
  
- **Machine Learning Models**: Implemented and evaluated using performance metrics:
    -1. Simple Linear Regression: *95.34% Accuracy*
    -2. Multiple Linear Regression: *99.21% Accuracy*
    -3. Random Forest Regression: *99.50% Accuracy*

## Contributing
Contributions are welcome! If you'd like to improve the project, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.

---
Developed by Saurav-exe (Saurav Pathare).

