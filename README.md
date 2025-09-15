# Netflix Movie Analysis

This project explores a dataset containing **9,827 movies** available on **Netflix**, with the goal of analyzing trends in movie genres, popularity, and user ratings. Using Python’s data manipulation and visualization libraries, the dataset was cleaned, transformed, and examined to uncover patterns that can help understand content preferences and release behaviors.

---

## ✅ Features & Objectives

* Perform data cleaning and preprocessing
* Handle missing values and duplicates
* Extract year from release dates and categorize numerical ratings
* Handle multi-genre data by splitting and restructuring
* Visualize trends using plots and charts
* Provide actionable insights based on the analysis

---

## 📂 Dataset Description

The dataset contains the following columns:

* **Release\_Date:** Date when the movie was released
* **Title:** Movie name
* **Popularity:** Score indicating the popularity of the movie
* **Vote\_Count:** Number of user votes
* **Vote\_Average:** Average rating given by users
* **Genre:** Movie genre(s)
* **Overview, Original\_Language, Poster\_Url:** Dropped during analysis as they were not necessary
* **Vote\_Category:** A new column created to classify movies based on their rating

---

## 🔑 Key Insights

### 1. **Most Common Genre**

The most frequent genre on Netflix is **Thriller**, closely followed by **Drama**. This suggests that content in these genres is consistently available and possibly popular among viewers.

### 2. **Genres with the Highest Votes**

Most votes fall under the **Good** category (\~12,500 votes), followed by **Average** (\~11,000 votes). The **Excellent** and **Poor** categories have significantly fewer votes.

### 3. **Movie with the Highest Popularity**

The highest popularity score belongs to **Spider-Man: No Way Home** (5083.95), which is classified under **Action**, **Adventure**, and **Science Fiction** genres.

### 4. **Movies with the Lowest Popularity**

There’s a tie between:

* **The United States vs. Billie Holiday (2021)** – Music, Drama, History
* **Threads (1984)** – War, Drama, Science Fiction
  Both with a popularity score of **13.35**.

### 5. **Yearly Trends**

A histogram analysis showed that certain years had more movies released than others, highlighting peaks in content production.

---

## 🛠 Tools & Libraries Used

* **Python** – for scripting and data manipulation
* **Pandas** – for cleaning, transforming, and analyzing data
* **NumPy** – for numerical operations
* **Matplotlib & Seaborn** – for creating insightful visualizations
* Data preprocessing techniques like:

  * Converting dates to year format
  * Handling missing data
  * Categorizing numerical columns
  * Splitting and exploding multi-value columns into individual rows

---

## 📈 How to Run This Project

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
2. Install required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Place the dataset file `mymoviedb.csv` in the project folder
4. Run the script:

   ```bash
   python netflix_analysis.py
   ```
5. Explore the generated plots and summaries

---

## 📂 Future Improvements

* Explore correlations between genres and viewer engagement
* Implement machine learning models for rating prediction
* Add interactive visualizations using tools like Plotly or Dash
* Incorporate more datasets for deeper analysis across platforms

---

## 📬 Connect

Feel free to ⭐ the repository if you find this useful! Contributions and suggestions are welcome.


Let me know if you want this README to include installation instructions for virtual environments, links to the dataset, or sample screenshots!
