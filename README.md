# Tiki Data Analysis and Web Scraping

## Project Overview

This project focuses on analyzing data from Tiki.vn, an e-commerce platform, to gain insights into various stores and their performance. Additionally, web scraping techniques are used to gather data from Tiki for further analysis. The project is divided into three main sections:

1. **Data Preprocessing**: Prepares and cleans data for analysis and clustering.
2. **Modeling and Analysis**: Applies machine learning algorithms for clustering and data insights.
3. **Web Scraping**: Scrapes data from Tiki.vn to collect store information for analysis.

## File Descriptions

### 1. `Data Preprocessing (Tiki).ipynb`
This notebook is responsible for the preprocessing of Tiki data. It includes steps for cleaning the data, handling missing values, and preparing the features for clustering and further analysis. The following key steps are included:
- **Feature Engineering**: Creation of new features for analysis.
- **Data Standardization**: Standardizing continuous variables for clustering algorithms.
- **Frequent Itemset Mining**: Identifying patterns to create binary features for further use.

### 2. `Model and Analysis (Tiki).ipynb`
This notebook applies various machine learning models to analyze the preprocessed Tiki data. The notebook includes:
- **Clustering Algorithms**: Usage of models like Birch, K-Means, and K-Prototypes to cluster stores based on their features.
- **Feature Selection**: Forward selection method is used to select the best binary features for clustering.
- **Evaluation**: Evaluation of different clustering models based on silhouette scores, Davies-Bouldin Index, etc.

### 3. `Model_and_Analysis_(Tiki)_1.ipynb`
A continuation or revised version of the `Model and Analysis (Tiki).ipynb`, this notebook includes further improvements to the clustering analysis. The notable changes include:
- **Hyperparameter Tuning**: Fine-tuning of clustering models for optimal results.
- **X-DBSCAN**: Experimentation with X-DBSCAN to handle noise and outliers in the data before applying K-Means.
- **Noise Removal**: Handling noisy data to improve the clustering performance.

### 4. `scrape_tiki.ipynb`
This notebook is used for scraping real estate data from Tiki.vn, focusing on gathering relevant information about stores and products. Key details scraped include:
- **Address, Price, Area, Bedrooms, Bathrooms**: Collecting data for real estate analysis.
- **Automation**: The script is designed to scrape multiple pages (up to page 300) automatically.
- **Data Storage**: The scraped data is stored in pandas DataFrames for easy analysis and visualization.

## How to Run

1. Clone this repository:
    ```bash
    git clone <repo_link>
    ```
2. Install necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebooks in the following order:
    1. `Data Preprocessing (Tiki).ipynb`
    2. `Model and Analysis (Tiki).ipynb` or `Model_and_Analysis_(Tiki)_1.ipynb` (improved version)
    3. `scrape_tiki.ipynb`

## Project Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- Scikit-learn
- BeautifulSoup (for web scraping)

## Future Work

- **Model Improvement**: Further tuning of clustering algorithms.
- **Additional Data Scraping**: Expanding the scope of web scraping to include more product categories.
- **Visualization**: Adding more advanced visualizations for store performance analysis.

## Contact

For any inquiries or collaboration, please contact [Your Name] at [your email].
