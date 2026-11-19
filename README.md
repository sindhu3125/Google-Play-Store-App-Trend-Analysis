# 📱 Google Play Store App Trend Analysis

## 📌 Project Overview

The Google Play Store contains thousands of applications across different categories, with varying ratings, reviews, download counts, sizes, and update frequencies. Understanding these patterns can help developers identify user preferences and explore factors associated with app popularity.

This project performs **Exploratory Data Analysis (EDA) on Google Play Store applications** to analyze app categories, ratings, reviews, installs, pricing, and update trends.

Using Python's data analysis and visualization libraries, the project cleans and processes the dataset, identifies patterns, and explores characteristics associated with popular and highly rated applications.

## 🎯 Objectives

- Analyze Google Play Store applications across different categories.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Analyze app ratings, reviews, installs, pricing, and sizes.
- Identify popular app categories based on downloads and user engagement.
- Explore relationships between ratings, reviews, installs, and other app attributes.
- Visualize insights using statistical plots and charts.
- Identify characteristics associated with successful applications.

## 📊 Dataset

**Dataset:** Google Play Store Apps Dataset

**Source:** Kaggle

**Data Type:** App information, user ratings, reviews, installs, and application attributes.

### Important Features

| Feature | Description |
|---|---|
| App | Application name |
| Category | Category to which the app belongs |
| Rating | User rating of the application |
| Reviews | Number of user reviews |
| Size | Application size |
| Installs | Number of app installations |
| Type | Free or paid application |
| Price | Application price |
| Content Rating | Age-based content classification |
| Genres | Application genre |
| Last Updated | Date of the last update |
| Android Version | Minimum Android version required |

## ⚙️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Data Collection:** Google Play Scraper
- **Development Environment:** Jupyter Notebook, VS Code

## 🧹 Data Cleaning and Preprocessing

The dataset was cleaned and prepared for analysis through the following steps:

- Handled missing values in relevant columns.
- Imputed missing categorical values using category-based median ratings where applicable.
- Cleaned rating, reviews, installs, size, and price columns by removing unwanted characters and converting them into appropriate data types.
- Removed non-English application entries for focused analysis.
- Identified duplicate application records and retained entries when the same app had differences in other attributes.
- Examined inconsistencies and invalid data values.
- Retained outliers instead of removing them to preserve potentially meaningful app popularity information.

## 🔬 Exploratory Data Analysis

The project explores different aspects of the Google Play Store dataset.

### 1. Category Analysis
- Analyze the distribution of apps across categories.
- Identify categories with the highest number of applications.
- Compare app ratings across different categories.

### 2. Rating Analysis
- Examine the distribution of application ratings.
- Identify highly rated and low-rated applications.
- Explore how ratings vary across app categories.

### 3. Reviews and User Engagement
- Analyze the number of reviews received by applications.
- Identify apps with high user engagement.
- Explore the relationship between reviews and app ratings.

### 4. Install Analysis
- Compare app installation counts across categories.
- Identify applications with high download counts.
- Explore install trends across free and paid applications.

### 5. Free vs Paid Apps
- Compare free and paid applications.
- Analyze pricing patterns.
- Explore differences in ratings, reviews, and installs.

### 6. App Update Analysis
- Analyze application update dates and update frequency.
- Explore how regularly applications are maintained.
- Examine the relationship between app updates and ratings or engagement.

### 7. App Success Analysis
Explore characteristics associated with potentially successful applications based on:

- High user ratings.
- Large number of reviews.
- High installation counts.
- Regular application updates.

A heuristic was used to identify potentially successful apps based on rating, reviews, installs, and update activity. These criteria are exploratory and do not represent a definitive measure of app success.

## 📈 Visualization Techniques

The analysis uses different visualization techniques to understand app trends and patterns, including:

- Bar charts for category comparisons.
- Histograms for rating and numerical distributions.
- Box plots for comparing distributions and identifying outliers.
- Scatter plots for relationships between ratings, reviews, and installs.
- Count plots for categorical feature analysis.
- Comparative visualizations for free vs paid applications.

## 🔍 Key Areas of Investigation

The project focuses on answering questions such as:

- Which categories have the highest number of applications?
- Which app categories receive higher average ratings?
- Do apps with more reviews tend to have higher ratings?
- Which applications have the highest number of installs?
- How do free and paid apps differ in popularity?
- Does application size have any relationship with installs or ratings?
- How frequently are successful applications updated?
- What characteristics are commonly observed among highly rated and popular apps?

## 🚀 Project Structure

```text
Google-Play-Store-App-Trend-Analysis/
│
├── dataset/
│   └── google_play_store.csv
│
├── notebooks/
│   └── Google_Play_Store_Analysis.ipynb
│
├── README.md
└── requirements.txt
```

*Note: Actual file and folder names may vary depending on the project repository.*

## 💻 Installation and Usage

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd Google-Play-Store-App-Trend-Analysis
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Load the Dataset

Place the dataset inside the `dataset` folder.

### 5. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `Google_Play_Store_Analysis.ipynb` and execute the cells sequentially to reproduce the analysis and visualizations.

## 🌟 Expected Outcome

The project provides insights into the Google Play Store app ecosystem by identifying category trends, user engagement patterns, rating distributions, installation behavior, pricing differences, and app update activity.

The analysis helps understand the characteristics of applications that attract users and receive positive feedback, providing useful insights for developers and businesses interested in mobile application trends.

## 🔮 Future Enhancements

- Build an interactive dashboard using Power BI or Streamlit.
- Analyze app reviews using Natural Language Processing.
- Track Google Play Store trends over time using updated datasets.
- Develop a data-driven app success classification model.
- Explore predictive models for ratings and app installs.

## 👩‍💻 Author

**Sindhu Reddyvari**

- GitHub: https://github.com/sindhu3125
