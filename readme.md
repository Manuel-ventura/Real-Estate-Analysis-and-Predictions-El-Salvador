# Real-Estate-Analysis-and-Predictions-El-Salvador 🏠

This project is a continuation of the web scraping project developed earlier to collect real estate data from El Salvador. The initial project can be found [here](https://github.com/Manuel-ventura/House-Scraper-El-Salvador).

## Overview 📊

This repository contains the analysis and predictive modeling of house prices in El Salvador. The main goals are to:

- Perform exploratory data analysis (EDA)
- Build and evaluate predictive models
- Develop an interactive dashboard to visualize the results

---

### Description

This repository contains a comprehensive analysis and predictive modeling project focused on real estate prices in El Salvador. Utilizing data collected from web scraping, the project includes data cleaning, exploratory data analysis (EDA), and the development of various predictive models. The project culminates in an interactive dashboard built with Dash, allowing users to visualize and explore the findings. Key components include regression models, decision trees, and random forest models, alongside visualizations of property density and feature importance. Ideal for data scientists, analysts, and real estate professionals interested in the El Salvador housing market.

---

## Project Structure 📁

```plaintext
Real-Estate-Analysis-and-Predictions-El-Salvador/
├── data/
│   ├── raw/
│   ├── processed/
├── notebooks/
│   ├── Property_Data_Cleaning.ipynb
│   ├── Real-Estate-Analysis-El-Salvador.ipynb
├── models/
│   ├── lin_reg_model.pkl
│   ├── tree_reg_model.pkl
│   ├── forest_reg_model.pkl
│   ├── tuned_rf_model.pkl
├── geo-map/
│   ├── property_clusters_map.html
│   ├── property_heat_map.html
├── app/
│   ├── dashboard.py
│   ├── styles.css
├── README.md
├── .gitignore
├── requirements.txt
```

## Getting Started 🚀

### Prerequisites

- Python 3.7+
- Virtual environment tools (venv or virtualenv)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Real-Estate-Analysis-and-Predictions-El-Salvador.git
   cd Real-Estate-Analysis-and-Predictions-El-Salvador
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the dashboard:
   ```bash
   python app/dashboard.py
   ```

## Notebooks 📓

### Property_Data_Cleaning.ipynb

- This notebook handles the data cleaning and preprocessing steps required for the analysis.

### Real-Estate-Analysis-El-Salvador.ipynb

- This notebook contains the exploratory data analysis and model building for predicting house prices.

## Models 🧠

- **Linear Regression Model**: `lin_reg_model.pkl`
- **Decision Tree Model**: `tree_reg_model.pkl`
- **Random Forest Model**: `forest_reg_model.pkl`
- **Tuned Random Forest Model**: `tuned_rf_model.pkl`

## Dashboard 📈

The interactive dashboard is built using Dash and contains the following components:

- Scatter plots of predicted vs. actual prices for different models
- Histogram of residuals for the tuned random forest model
- Feature importance bar chart for the random forest model
- Heat map of property densities in El Salvador

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Acknowledgements 🙏

- Special thanks to all contributors and the open-source community.

---

Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback is highly appreciated! 🌟

```

```
