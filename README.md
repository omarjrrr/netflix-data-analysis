# netflix-data-analysis
# Netflix Data Cleaning and Visualization

This project performs data cleaning, feature engineering, and visualization on a dataset of Netflix Movies and TV Shows. It aims to extract insights about content trends, genres, durations, and more.

## 📁 Dataset

- Source: Netflix Titles Dataset
- Contains over 8,800 entries about movies and TV shows available on Netflix.
- Columns include title, director, cast, country, rating, date added, duration, and genre.

## 🧹 Features of the Project

### Data Cleaning
- Handled missing values in `director`, `cast`, `country`, and `rating`.
- Parsed and split the `duration` column into numeric value and type (`min`, `Season`).
- Converted `date_added` to datetime format.

### Feature Engineering
- Extracted `year_added` and `month_added` from `date_added`.
- Calculated number of cast members per title.
- Counted the number of genres per title.
- Created a flag for multiple directors.

### Visualizations
- 📈 Content released per year by type (Movie vs TV Show)
- 🌍 Top 10 countries producing the most content
- 🔞 Distribution of ratings
- 🎭 Top genres on Netflix
- 🎬 Top directors by number of titles
- ⌛ Distribution of movie durations
- 📺 Season counts for TV Shows
- 👥 Distribution of cast members per title

## 🛠 Libraries Used
- pandas
- matplotlib
- seaborn

## 💡 How to Run
1. Clone this repository
2. Install the required libraries:
