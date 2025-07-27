Here’s a detailed **GitHub project description** for your Netflix Data Visualization notebook that you can include in your repository `README.md`:

---

## 📊 Netflix Data Visualization Project

This project analyzes and visualizes Netflix’s public dataset (`netflix_titles.csv`) using **Python**, **Pandas**, and **Matplotlib**. The goal is to gain insights into Netflix’s content library by exploring types of shows, ratings, durations, release trends, and country-wise distributions.

---

### 🔧 Technologies Used

* **Python 3**
* **Pandas** for data manipulation
* **Matplotlib** for data visualization
* **Jupyter Notebook**

---

### 📁 Dataset

* Source: [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
* File Used: `netflix_titles.csv.zip`

---

### 📈 Visualizations Created

#### 1. **Movies vs. TV Shows Count**

A bar chart comparing the total number of Movies and TV Shows available on Netflix.

#### 2. **Content Ratings Distribution**

A pie chart showing the percentage distribution of various content ratings (like TV-MA, PG, R, etc.).

#### 3. **Movie Duration Distribution**

A histogram representing the duration of movies in minutes.

#### 4. **Release Year vs. Number of Shows**

A scatter plot showing the number of shows released each year.

#### 5. **Top 10 Countries by Content**

A bar chart displaying countries that produce the highest number of Netflix titles.

#### 6. **Movies vs TV Shows Over Time**

A line plot showing the trend of movie and TV show releases over the years.

---

### 🧹 Data Cleaning Steps

* Dropped null values from important columns like `type`, `release_year`, `rating`, `country`, and `duration`.
* Extracted numeric duration from movie entries.
* Grouped and counted relevant data for visualizations.

---

### 📂 Output Files

Each plot is saved as a `.png` image:

* `movies_vs_tvshows.png`
* `content_rating_pie.png`
* `movie_duration_histogram.png`
* `release_year_Scatter.png`
* `top10_countries.png`
* `movies_tv_shows_comparison.png`

---

### 📌 How to Run

1. Clone this repository.
2. Ensure you have `matplotlib` and `pandas` installed:

   ```bash
   pip install matplotlib pandas
   ```
3. Open `Netflix_Visualization.ipynb` in Jupyter Notebook or Vs code.
4. Run all cells to generate and save the plots.

---

### 💡 Insights

* Netflix has more movies than TV shows.
* Majority of content falls under TV-MA rating.
* Most movies are between 80–100 minutes.
* USA dominates content production on Netflix.
* There's a clear growth in Netflix content over the years, especially after 2015.


