# Analyzing-Movie-Ratings-from-Rotten-Tomatoes
<!-- PROJECT BANNER -->
<p align="center">
  <img src="Movie Ratings from Rotten Tomatoes/Images/cover.png" alt="Analyzing Movie Ratings from Rotten Tomatoes" width="800"/>
</p>

<!-- PROJECT BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas" />
  <img src="https://img.shields.io/badge/EDA-Complete-brightgreen" />
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%26%20Seaborn-orange" />
  <img src="https://img.shields.io/badge/Status-Finished-lightgrey" />
</p>

<h1 align="center">🎬 Analyzing Movie Ratings from Rotten Tomatoes</h1>

---

## 📌 Project Objective
This project analyzes movie rating data from **Rotten Tomatoes**, comparing critic reviews (**Tomatometer**) with audience feedback.  
Focusing on films released from **2010 onward**, the goal is to uncover trends in genre preferences, rating patterns, and audience engagement.  

The workflow covers:
- **Data Cleaning**
- **Feature Engineering**
- **Exploratory Data Analysis (EDA)**
- **Visual Storytelling through Insights**

---

## 🧰 Tools & Technologies
- **Python 3** – Core programming language  
- **Pandas** – Data manipulation & filtering  
- **NumPy** – Conditional feature creation  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive development environment  

---

## 🗂️ Dataset Overview
- **Source:** Maven Analytics – Rotten Tomatoes dataset  
- **Initial Size:** `16,638 rows × 9 columns`  
- **Key Columns Used:**  
  - `movie_title`  
  - `rating`  
  - `genre`  
  - `in_theaters_date`  
  - `runtime_in_minutes`  
  - `tomatometer_rating`  
  - `tomatometer_count`  
  - `audience_rating`  
  - `audience_count`

---

## 🧹 Step A: Data Cleaning & Preparation
- Removed irrelevant columns  
- Converted `in_theaters_date` to **datetime** format  
- Filtered for movies released in **2010 or later**  
- Created a filtered dataset `movies_popular` with **316 movies** having audience count > 100K  

---

## 🛠️ Step B: Feature Engineering
- Extracted **release year** from `in_theaters_date`  
- Created binary genre flags for:  
  - Animation  
  - Action & Adventure  
  - Comedy  

---

## 📊 Step C: Exploratory Data Analysis
**Key Observations:**
- **PG-13**, **R**, and **PG** are the most common ratings  
- **PG-13** films have the highest average audience rating  
- Animated films rate higher with both critics & audiences  
- Comedy films tend to have lower ratings overall  
- *Shutter Island* is an outlier with **2M+ audience reviews**  

---

## 📈 Visualizations & Insights
- **Top 10** longest movies  
- **Scatter plot**: critic rating vs. runtime  
- **Top 10** most-rated movies by critics  
- **Correlation heatmap** of numeric features  
- **Pairplot** for distribution & relationship analysis  
- **Genre frequency bar chart**  
- **Stacked bar charts** showing ratings by genre  

---

## 🔍 Key Insights
✅ Audience ratings are consistently higher than critic ratings  
✅ Animated movies perform best across both rating types  
✅ Comedy & Drama dominate as the most common genres  
✅ No strong correlation between runtime & ratings  
✅ Post-2010 surge in highly rated releases  
✅ *Shutter Island* shows exceptional audience engagement  

---

<p align="center">📌 Created with ❤️ using Python, Pandas, and Seaborn</p>

