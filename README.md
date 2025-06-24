#  Netflix Movies and TV Shows Analysis

##  Project Description

This project presents an in-depth Exploratory Data Analysis (EDA) of the Netflix Movies and TV Shows dataset, leveraging powerful Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The primary objective is to derive meaningful insights and uncover hidden patterns within the dataset by performing thorough data cleaning, preprocessing, and visualization.

Through this analysis, we examine key aspects of Netflix's content library, including the distribution between Movies and TV Shows, temporal trends in content release over the years, variations in content production across different countries, and runtime/duration patterns. By visually representing these patterns, the project aims to highlight content preferences, geographic production diversity, and how Netflix's offerings have evolved over time.

This EDA serves as a foundational step in understanding the structure of entertainment datasets and can be extended to drive further applications like recommendation systems, trend forecasting, or content strategy analysis. The project is a great demonstration of how data science can be applied to real-world entertainment industry data to extract actionable insights.

---

## 📁 Dataset
**Source:** [Kaggle - Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset contains over 10,000+ titles with features like:
- `title`
- `director`
- `cast`
- `country`
- `release_year`
- `duration`
- and more.

---

##  Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

##  Key Insights & Visualizations

This project visualizes key trends and patterns in Netflix content. The analysis includes:

- Distribution of Movies vs TV Shows  
- Content release trend over the years  
- Country-wise content production  
- Duration distribution across content types  
- Ratings of Netflix content  
- Annual content release count  
- Top genres on Netflix  

> 🔽 Visualizations are stored in the `screenshots/` folder.

### 🔹 Sample Visuals

![Movies vs TV Shows](screenshots/movies_vs_tv_shows.png)  
*Distribution of content type on Netflix*

![Content Release by Year](screenshots/count_release_in_year_vs_count.png)  
*Annual content release trend*

![Top Countries](screenshots/country_wise_content_production.png)  
*Top countries by number of titles*

![Ratings Distribution](screenshots/ratings_vs_count.png)  
*Count of content by maturity rating*

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/AbdullahShariq/Netflix-EDA.git

# Navigate to the project directory
cd Netflix-EDA

# Launch the Jupyter Notebook
jupyter notebook "Netflix Movies and TV Shows Analysis.ipynb"
```


