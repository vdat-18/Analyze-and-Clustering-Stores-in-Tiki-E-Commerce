# 📊 Tiki.vn Data Analysis & Web Scraping Project

![Tiki Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Tiki_VN_Logo.svg/512px-Tiki_VN_Logo.svg.png)

## 🔍 **Project Overview**
This project focuses on data analysis and web scraping of Tiki.vn, a major e-commerce platform in Vietnam. It involves:
- Preprocessing and cleaning data for analysis.
- Applying machine learning models for clustering Tiki stores.
- Scraping real estate data from Tiki.vn for deeper insights.

---

## 📂 **File Structure**

| File Name                     | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| `Data Preprocessing (Tiki).ipynb` | Prepares and cleans the Tiki dataset, handles missing values, and creates new features for clustering. |
| `Model and Analysis (Tiki).ipynb` | Implements clustering algorithms like Birch, K-Means, and K-Prototypes, along with feature selection. |
| `Model_and_Analysis_(Tiki)_1.ipynb` | An improved version of the model notebook, adding hyperparameter tuning, X-DBSCAN, and noise removal. |
| `scrape_tiki.ipynb`            | Web scraping real estate data from Tiki.vn, including address, price, and area details. |

---

## 🚀 **Key Features**

### 1. `Data Preprocessing (Tiki).ipynb`
- **Data Cleaning**: Handles missing values and standardizes continuous features.
- **Feature Engineering**: Generates new binary features from frequent itemsets.
- **Standardization**: Prepares continuous variables for machine learning models.
  
### 2. `Model and Analysis (Tiki).ipynb`
- **Clustering Algorithms**: Birch, K-Means, and K-Prototypes applied to segment stores.
- **Feature Selection**: Forward selection of binary features for optimal clustering.
- **Evaluation Metrics**: Silhouette scores, Davies-Bouldin Index, and other performance indicators.

### 3. `Model_and_Analysis_(Tiki)_1.ipynb`
- **X-DBSCAN**: Handles noise in the data for better clustering results.
- **Noise Removal**: Removes outliers before applying K-Means for improved performance.
- **Hyperparameter Tuning**: Optimizes clustering models for better segmentation.

### 4. `scrape_tiki.ipynb`
- **Web Scraping**: Automates scraping of real estate listings, capturing vital details such as address, price, bedrooms, and area.
- **Multi-page Scraping**: Efficiently scrapes data from up to 300 pages, gathering comprehensive insights.
- **Data Storage**: Collected data is stored in a structured pandas DataFrame for easy analysis.

---

## ⚙️ **How to Use**

1. **Clone the repository**:
```bash
git clone <repository_link>
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Run the notebooks:
- Start with Data Preprocessing (Tiki).ipynb.
- Move on to the analysis notebooks (Model and Analysis (Tiki).ipynb or Model_and_Analysis_(Tiki)_1.ipynb).
- Finally, run scrape_tiki.ipynb for data scraping.
## 📊 Project Flow
```bash 
graph TD;
    A[Data Preprocessing] --> B[Clustering Models]
    B --> C[Birch & K-Means]
    C --> D[X-DBSCAN & Noise Removal]
    D --> E[Final Clusters]
    A --> F[Web Scraping]
    F --> G[Data Collection]
    G --> H[Data Analysis]
```
## 🛠 Technologies Used
- Python 3.x: The core programming language used.
- Pandas: For data manipulation and analysis.
- Scikit-learn: Applied for machine learning models and clustering.
- BeautifulSoup: Used for web scraping.
- Jupyter Notebooks: For interactive analysis and visualization.
## 📈 Future Work
- Model Optimization: Further tuning and experimentation with clustering algorithms.
- Advanced Visualizations: Adding more intuitive graphs and charts to visualize insights.
- Extended Web Scraping: Expanding the scraping capabilities to include additional product categories and features.
## 💬 Contact Information
For any questions or collaborations, feel free to reach out:
Name: Dat Nguyen <br>
Email: ngvdat.w@gmail.com <br>
LinkedIn: https://www.linkedin.com/in/nguyen-dat-399305247/

Name: Your Name
Email: your.email@example.com
LinkedIn: Your LinkedIn
