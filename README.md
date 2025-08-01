# 📊 Netflix Data Visualization Project

This project analyzes and visualizes the Netflix Titles dataset using Python libraries like `pandas` and `matplotlib`. It showcases various trends in Netflix content such as types, durations, ratings, and release patterns.

## 🗂 Dataset

The dataset used is [netflix_titles.csv](https://www.kaggle.com/datasets/shivamb/netflix-shows), which contains information about movies and TV shows available on Netflix as of 2021.

### Columns Used:
- `type` – Movie or TV Show
- `title` – Name of the content
- `country` – Country of origin
- `release_year` – Year of release
- `rating` – Age rating (e.g., TV-MA, PG-13)
- `duration` – Length of content

## 🧹 Data Cleaning

- Removed rows with missing values in key columns: `type`, `release_year`, `rating`, `country`, `duration`
- Converted movie durations from string to integer

## 📈 Visualizations

The project generates a multi-subplot figure with the following plots:

1. **Bar Chart** – Number of Movies vs TV Shows
2. **Pie Chart** – Distribution of Top 6 Content Ratings
3. **Histogram** – Distribution of Movie Durations
4. **Scatter Plot** – Content Released Over the Years
5. **Horizontal Bar Chart** – Top 10 Countries by Number of Titles
6. **Line Plot** – Number of Movies Released Each Year
7. **Line Plot** – Number of TV Shows Released Each Year

All visualizations are arranged in a single canvas and exported as a high-resolution PDF.

## 📁 Output

The visualization is saved as:

```bash
Netflix Data Visualizations.pdf
