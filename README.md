# 🎬 Netflix Movies & TV Shows EDA

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Netflix Movies & TV Shows dataset**.  
The primary goal of this analysis is to uncover insights about the available content on Netflix, including:
- Genres  
- Ratings  
- Release years  
- Content type (Movie or TV Show)  
- Other factors that provide valuable insights into Netflix's catalog.  

The dataset used contains a list of movies and TV shows available on Netflix.

---

## 📊 Dataset
The dataset is available on **Kaggle** and includes the following columns:

- `show_id`: Unique identifier for each movie or TV show  
- `type`: Type of the content (Movie or TV Show)  
- `title`: The title of the movie or TV show  
- `director`: Director of the content  
- `cast`: Main actors/actresses  
- `country`: The country where the content was produced  
- `date_added`: The date when the content was added to Netflix  
- `release_year`: The year the content was released  
- `rating`: The content's rating (e.g., PG, PG-13, R)  
- `duration`: Duration of the content (for movies: in minutes, for TV shows: number of seasons)  
- `genre`: Genre of the content (e.g., Action, Drama, Comedy)  
- `description`: Short description of the content  

📂 **Source**: [Netflix Movies & TV Shows Dataset on Kaggle](https://www.kaggle.com/datasets/paramvir705/netflix-dataset))

---

## 🔎 Analysis Summary

### 1️⃣ Data Cleaning and Preprocessing
- **Handling Missing Values** → Removed rows with missing critical data  
- **Date Conversion** → Converted `date_added` to proper datetime format  
- **Type Conversion** → Converted `release_year` and `duration` into numeric formats for analysis
- **Dividing the Column** → Divided the 'Listed in' column into tv_shows and movies for better analysis  

### 2️⃣ Exploratory Data Analysis (EDA)
- **Content Type Distribution** → Movies vs. TV Shows  
- **Top Countries** → Countries with the highest release of content on Netflix
- **Types of Ratings** → Various types of ratings gives for the movies/TV shows
- **Number of Releases** → Total release on Netflix based on each year.
- **Genre Analysis** → Distribution of genres across Netflix
- **Average Release** → Average number of releases of both Movies and TV shows
- **Top Countries** → Countries with the highest number of movies vs TV show release
- **Ratings Analysis** → Ratings distribution & comparison across content types  
- **Duration Analysis** → Distribution of movie lengths & TV show seasons  

### 3️⃣ Key Insights
- 🎥 **Content Type**: Netflix has more **movies** than TV shows, but TV shows are steadily increasing  
- 🎭 **Popular Genres**: Action, Drama, and Comedy dominate Netflix's catalog  
- 🌍 **Top Countries**: United States, India, and the United Kingdom lead in content production  
- ⭐ **Rating Trends**: Most content is rated **PG** or **TV-MA**, showing wide audience targeting  
- 📅 **Release Year Trends**: Significant rise in **Netflix Originals** and content after 2015  
- 🕒 **Duration Analysis**: Most of the people tend to watch more TV shows because of the short time duration rather than movies.
  
---

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---
