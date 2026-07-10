# Netflix Data Analysis Using Python

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset using Python. The objective is to analyze Netflix's content library by cleaning the dataset, exploring trends, and visualizing insights related to content type, ratings, release years, countries, genres, and durations.

---

## Objectives

- Understand the structure of the Netflix dataset.
- Clean and preprocess the data.
- Perform exploratory data analysis (EDA).
- Create meaningful visualizations.
- Extract actionable insights from the data.

---

## Dataset

**Dataset:** Netflix Movies and TV Shows

The dataset contains the following attributes:

- Show ID
- Type (Movie/TV Show)
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre (Listed In)
- Description

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb
├── netflix.csv
├── README.md
└── images/
    ├── dataset_preview.png
    ├── missing_values.png
    ├── content_type_distribution.png
    ├── ratings_distribution.png
    ├── release_year_trend.png
    ├── top_countries.png
    ├── movie_duration_distribution.png
    └── correlation_heatmap.png
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
```

Navigate to the project directory:

```bash
cd Netflix-Data-Analysis
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook:

```
Netflix_Data_Analysis.ipynb
```

---

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Checked dataset dimensions and column information.
- Identified missing values.
- Removed duplicate records.
- Handled null values.
- Converted date columns into appropriate formats.
- Verified cleaned data before analysis.

---

## Exploratory Data Analysis

The analysis includes:

### Dataset Overview

- Dataset shape
- Column information
- Data types
- Summary statistics

### Missing Value Analysis

- Missing value count
- Missing value visualization

### Content Type Analysis

- Movies vs TV Shows
- Distribution of content types

### Content Rating Analysis

- Distribution of content ratings
- Most common ratings

### Release Year Analysis

- Content released over the years
- Trend analysis

### Country Analysis

- Countries contributing the highest amount of Netflix content

### Movie Duration Analysis

- Distribution of movie durations

### TV Show Season Analysis

- Distribution of number of seasons

### Genre Analysis

- Most common genres available on Netflix

---

## Visualizations

The project includes visualizations such as:

- Count Plots
- Bar Charts
- Histograms
- Heatmaps
- Line Charts
- Pie Charts

---

## Key Insights

- Movies constitute the majority of Netflix's content library.
- TV-MA is the most common content rating.
- The United States contributes the highest number of titles.
- Netflix experienced rapid content growth after 2015.
- Drama and International Movies are among the most frequent genres.
- Most movies have durations ranging from 80 to 120 minutes.

---

## Results

The project demonstrates how exploratory data analysis can reveal meaningful patterns from large datasets. The visualizations provide insights into Netflix's content distribution, production trends, ratings, and genre preferences.

---

## Future Enhancements

- Develop an interactive dashboard using Streamlit.
- Perform sentiment analysis on content descriptions.
- Build recommendation models.
- Deploy the project as a web application.

---

## Screenshots

Include screenshots of the following in the `images` folder:

- Dataset Preview
- Missing Value Analysis
- Content Type Distribution
- Ratings Distribution
- Release Year Trend
- Top Producing Countries
- Movie Duration Distribution
- Correlation Heatmap

---

## Author

**Bheemaiah**

Software Engineering Student

GitHub: https://github.com/your-username

LinkedIn: https://www.linkedin.com/in/your-profile/

---

## License

This project is intended for educational and learning purposes.
