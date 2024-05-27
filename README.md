
# Real Estate Data Analysis

This repository contains scripts and data for analyzing real estate properties. The project includes data loading, preprocessing, web scraping, exploratory data analysis, and basic modeling.

## Files

### 1. `Project_Data.csv`
This CSV file contains real estate property data with the following columns:
- `Unnamed: 0`: An index column.
- `bedrooms`: The number of bedrooms in the property.
- `price`: The listed price of the property.
- `bathrooms`: The number of bathrooms in the property.
- `MLS_Number`: The MLS (Multiple Listing Service) number.
- `sq_ft`: The square footage of the property.
- `address`: The address of the property, which sometimes includes status information (e.g., Pending, Active).

#### Metrics:
- **Number of Records**: 1,018
- **Price Range**: $56,800 to $998,888
- **Bedroom Range**: 1 to 3 bedrooms
- **Bathroom Range**: 1 to 3 bathrooms
- **Square Footage Range**: 670 sq ft to 1,866 sq ft

### 2. `Data_Analysis_Analysis_Part.ipynb`
This Jupyter notebook contains data analysis scripts including:
- **Data Loading and Preprocessing**: Reading and cleaning the data.
- **Exploratory Data Analysis (EDA)**: Generating summary statistics and visualizations.
- **Modeling and Evaluation**: Building and evaluating machine learning models.
- **Conclusions and Recommendations**: Final insights and actionable recommendations.

### 3. `Data_Analysis_Web_Scraping.ipynb`
This Jupyter notebook focuses on web scraping tasks, including:
- **Library Imports**: Importing necessary libraries (e.g., BeautifulSoup, requests, pandas).
- **Web Scraping Logic**: Extracting data from web pages.
- **Data Cleaning and Storage**: Cleaning and storing the scraped data.
- **Basic Analysis**: Initial analysis of the scraped data.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- pandas
- BeautifulSoup
- requests

### Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/real-estate-data-analysis.git
cd real-estate-data-analysis
```

Install the required packages:
```bash
pip install -r requirements.txt
```

Feel free to modify the content according to your project's specific details or additional instructions.
