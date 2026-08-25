🎧 Spotify Data Analytics
📌 Project Overview

This project analyzes Spotify track data to uncover insights about song characteristics, popularity trends, and audio features.
It demonstrates how to collect, clean, and analyze Spotify data using Python, SQL, and MySQL integration — providing a hands-on example of data-driven music analytics.

🧩 Features

Extracts Spotify track data from pre-defined URLs

Stores and manages data in a MySQL database

Performs SQL queries to retrieve, clean, and analyze the dataset

Conducts Python-based analysis for metrics like:

Top artists and genres

Correlation between features (danceability, energy, valence, etc.)

Popularity trends

Supports CSV file processing for reproducibility

📂 Project Structure
spotify_data_analytics-main/
│
├── spotify.py                # Main Python analysis script
├── spotify_mysql.py          # Script for connecting and uploading data to MySQL
├── spotify_mysql_urls.py     # Script containing Spotify track URLs or endpoints
├── spotify.sql               # SQL schema and queries for database setup
├── spotify_track_data.csv    # Dataset containing Spotify track details
├── track_urls.txt            # Text file with track or playlist URLs
└── README.md                 # Project documentation

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/cyrildude77/spotify_data_analytics.git
cd spotify_data_analytics

2️⃣ Install Dependencies

Make sure you have Python 3.x installed, then install required packages:

pip install pandas mysql-connector-python spotipy

3️⃣ Set Up MySQL

Create a database named spotify_db

Run the spotify.sql script to create necessary tables:

mysql -u root -p spotify_db < spotify.sql

4️⃣ Run the Python Scripts

To upload data to MySQL:

python spotify_mysql.py


To perform Spotify data analysis:

python spotify.py

📊 Example Insights

Most Popular Artists: Identify artists dominating the Spotify charts

Feature Correlations: Understand how tempo, energy, or danceability affect popularity

Data Visualizations: Create graphs for better trend visualization (can integrate Matplotlib/Seaborn)

💡 Future Enhancements

Add interactive dashboards using Power BI or Tableau

Automate data collection using Spotify API

Deploy as a web app (Flask or Streamlit)
