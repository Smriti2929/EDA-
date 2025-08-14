🎥 Anime Recommendation EDA

An Exploratory Data Analysis (EDA) of the Kaggle Anime Recommendations Database.
This project analyzes anime ratings in relation to their genres, types, and number of episodes, providing insights into viewing preferences and patterns.

Note: The dataset does not include the Big 3 (Naruto, One Piece, and Bleach).

📊 Objectives

Explore the relationship between genre, type, episodes, and ratings.

Identify the most consumed genres.

Find preferred anime types by rating.

Determine the most common episode counts.

Highlight the top 5 highest-rated anime.

📂 Dataset

Source: Kaggle – Anime Recommendations Database

anime.csv – Contains details of anime such as name, genre, type, episodes, and rating.

rating.csv – Contains user ratings for different anime.

🔍 Analysis Performed

Data Preparation & Cleaning

Handled missing values in rating, genre, type, and episodes.

Removed unused columns.

Exploratory Analysis

Top Genres: Counted and visualized the most popular genres.

Type Preference: Analyzed average ratings by anime type (e.g., TV, OVA, Movie).

Episode Distribution: Found the most common number of episodes.

Top Anime: Extracted the 5 anime with the highest ratings.

Multi-factor Ratings: Grouped ratings by combinations of genre, type, and episodes.

Visualizations

Pie charts for genre and episode distribution.

Bar charts for top genres and ratings by type.

Combined factor plots for highest-rated combinations.

📈 Key Insights

Shorter series (1–12 episodes) often have higher ratings due to concise storytelling.

Drama, Action, and Fantasy genres paired with TV or OVA formats tend to score high.

Movies and OVAs with genres like Romance or Sci-Fi often rank well.

Top 5 Anime by Rating: Derived from the cleaned dataset (specific names in notebook).

🛠 Technologies Used

Python

Pandas & NumPy – Data cleaning and transformation

Matplotlib & Seaborn – Visualization

opendatasets – Kaggle dataset download

📌 Future Improvements

Interactive dashboard using Plotly or Dash.

NLP-based anime synopsis analysis for content-based recommendations.

Trend analysis over release years.

🚀 How to Run

Clone the repository:

git clone https://github.com/<your-username>/anime-eda.git


Install dependencies:

pip install pandas numpy matplotlib seaborn opendatasets


Run the notebook:

jupyter notebook Anime_EDA.ipynb


🤝 Contributing

Pull requests are welcome! Please open an issue first to discuss any major changes.
