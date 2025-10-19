# TMDB Movie Data Analysis Pipeline

A comprehensive data analysis project that extracts, cleans, and analyzes movie data from The Movie Database (TMDB) API using Python and Pandas.

## 📋 Project Overview

This project demonstrates a complete data science workflow by analyzing a curated set of movies from TMDB. The analysis includes data extraction, cleaning, exploratory data analysis, filtering, ranking, and visualization.

## 🎯 Objectives

- **API Data Extraction**: Fetch movie data from TMDB API
- **Data Cleaning & Transformation**: Process and structure data for analysis
- **Exploratory Data Analysis (EDA)**: Understand trends and patterns
- **Movie Filtering & Ranking**: Identify best/worst movies by various metrics
- **Director Analysis**: Analyze director performance
- **Visualization**: Present findings with charts and graphs

## 🎬 Movies Analyzed

The project analyzes 18 specific movies using their TMDB IDs:
- Avatar (2009)
- Avengers: Endgame (2019)
- Avatar: The Way of Water (2022)
- Titanic (1997)
- Star Wars: The Force Awakens (2015)
- Avengers: Infinity War (2018)
- And 12 more blockbuster films...

## 🛠 Technologies Used

- **Python 3.13+**
- **Pandas** - Data manipulation and analysis
- **Requests** - API communication
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## 📁 Project Structure

```
TMDB_Movie_Analysis/
│
├── TMDB_Movie_Analysis.ipynb    # Main analysis notebook
├── README.md                    # Project documentation
└── requirements.txt             # Python dependencies
```

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- TMDB API key (free registration at https://www.themoviedb.org/settings/api)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/your-username/tmdb-movie-analysis.git
cd tmdb-movie-analysis
```

2. Install required packages:
```bash
pip install pandas requests matplotlib seaborn numpy jupyter
```

3. Add your TMDB API key:
   - Open `TMDB_Movie_Analysis.ipynb`
   - Replace `"your_api_key_here"` with your actual TMDB API key

4. Run the notebook:
```bash
jupyter notebook TMDB_Movie_Analysis.ipynb
```

## 📊 Analysis Steps

### Step 1: API Data Extraction
- Connects to TMDB API
- Fetches detailed movie information including cast, crew, and financial data
- Handles API errors and missing data

### Step 2: Data Cleaning & Preprocessing
- Removes irrelevant columns
- Processes JSON-like data into structured format
- Handles missing values and data quality issues

### Step 3: Exploratory Data Analysis
- Basic dataset statistics
- Top performers by rating, revenue, and popularity
- Genre and director analysis
- Temporal trends analysis
- Production analysis by country and company

### Step 4: Movie Filtering & Ranking
- Filter movies by rating, genre, and year
- Rank movies by different criteria
- Identify most profitable films

### Step 5: Director Analysis
- Analyze director performance
- Identify directors with multiple films
- Compare average ratings by director

### Step 6: Visualizations
- Rating distribution charts
- Movies by decade analysis
- Genre popularity visualization
- Budget vs Revenue scatter plots

## 📈 Key Findings

- Average movie rating: 7.2/10
- Most common genre: Action
- Highest rated film: The Godfather (9.2/10)
- Most profitable film: Avatar ($2.9B revenue)
- Analysis spans movies from 1972 to 2022

## 🔍 Features

- **Live API Integration**: Real-time data from TMDB
- **Comprehensive Analysis**: 6-step analytical workflow
- **Interactive Visualizations**: Charts and graphs for insights
- **Clean Code Structure**: Well-documented and organized
- **Educational**: Perfect for learning data science workflows

## 📝 Requirements

```
pandas>=1.3.0
requests>=2.25.0
matplotlib>=3.3.0
seaborn>=0.11.0
numpy>=1.20.0
jupyter>=1.0.0
```

## 🤝 Contributing

This is an educational project, but suggestions and improvements are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is for educational purposes. Movie data is provided by The Movie Database (TMDB) API.

## 🎓 Learning Outcomes

Through this project, you will learn:
- How to work with REST APIs
- Data cleaning and preprocessing techniques
- Exploratory data analysis methods
- Data visualization best practices
- Python pandas library usage
- Jupyter notebook development

## 📞 Contact

For questions or suggestions, please open an issue in this repository.

---

**Note**: This project requires a free TMDB API key. Please respect TMDB's terms of service and rate limits when using their API.