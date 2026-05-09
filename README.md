# 🎬 Movie Industry Analytics Dashboard

## 📌 Project Overview

This end-to-end data analytics project explores movie industry trends using Python and Power BI. The analysis focuses on genres, ratings, popularity, audience engagement, release trends, and language distribution to uncover meaningful insights from movie data. The goal of this analysis is to discover meaningful insights about audience behavior, movie production trends, and genre distribution using Python and Power BI.

The project demonstrates the complete data analytics workflow:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Dashboard Development
* Insight Generation
* Business Storytelling

---

# 📊 Dashboard Preview

> ![Dashboard Screenshot](dashboard_netflix_movies_analysis.png)


# 🛠 Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* Microsoft Power BI
* GitHub

---

# 📂 Dataset Information

The dataset contains movie-related information such as:

| Column            | Description             |
| ----------------- | ----------------------- |
| Title             | Movie title             |
| Genre             | Movie genre             |
| Popularity        | Popularity score        |
| Vote_Average      | Average movie rating    |
| Vote_Count        | Total audience votes    |
| Release_Date      | Movie release date      |
| Original_Language | Original movie language |

---

# 🧹 Data Cleaning Process

The following preprocessing steps were performed:

* Removed unnecessary columns such as `Overview` and `Poster_Url`
* Converted `Release_Date` into datetime format
* Extracted release year from the date column
* Split and exploded the `Genre` column for accurate genre analysis
* Removed duplicate records
* Handled missing values
* Filtered unrealistic high-rated movies with very low vote counts

---

# 📈 Exploratory Data Analysis (EDA)

The analysis focused on answering important business and audience-related questions:

* Which genres dominate movie production?
* Are highly rated movies always popular?
* How has movie production changed over time?
* Which languages dominate the dataset?
* What relationship exists between ratings, popularity, and vote counts?

---

# 📌 Key Insights

* Drama is the most dominant genre in the dataset, accounting for nearly 39.4% of all movies, followed by Comedy and Action.

* The number of movies released per year increased significantly after 2000, reflecting major growth in global film production over time.

* The analysis indicates that highly rated movies are not always the most popular, suggesting that audience popularity depends on factors beyond ratings alone.

* Correlation analysis revealed weak relationships among popularity, ratings, and vote counts, indicating that movie success is influenced by multiple independent factors.

* English-language movies dominate the dataset, while other languages contribute smaller shares to overall movie production.

* Movies with higher vote counts generally tend to receive slightly better ratings, suggesting that audience engagement may influence rating reliability.

* A noticeable decline in movie releases was observed during the COVID-19 period (2019–2020), indicating temporary disruption in film production activity.

---

# 📊 Power BI Dashboard Features

The interactive dashboard includes:

* KPI Cards
* Genre Distribution Analysis
* Ratings vs Popularity Scatter Plot
* Movie Release Trend Analysis
* Interactive Filters & Slicers

---

# 🚀 How to Run the Project

1. Clone this repository
2. Open the Jupyter Notebook
3. Run the notebook cells step-by-step
4. Open the Power BI dashboard file
5. Explore the interactive visuals and insights

---

# 📌 Conclusion

This project demonstrates practical skills in data cleaning, exploratory data analysis, data visualization, and dashboard storytelling. It highlights how data analytics can uncover meaningful insights from movie industry data and support data-driven decision-making.

---

# 📬 Contact

If you liked this project or want to connect, feel free to reach out through GitHub.
