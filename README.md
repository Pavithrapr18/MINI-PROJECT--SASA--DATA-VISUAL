Spotify Artist Streaming Analytics — Data Visualization
📊 Project Overview

Spotify Artist Streaming Analytics is a data visualization project that analyzes Spotify track and artist data using Microsoft Excel and Power BI. The project focuses on identifying patterns in streaming performance, artist popularity, music genres, release trends, and audio characteristics.

The cleaned dataset is transformed into an interactive Power BI dashboard that presents the findings through charts, KPI cards, maps, and other visualizations.

🎯 Objectives

Analyze artist and track streaming performance.
Identify the most streamed artists and tracks.
Analyze streaming performance across different genres.
Study music release patterns by year, month, quarter, and day.
Examine audio characteristics such as danceability, energy, tempo, loudness, and instrumentalness.
Compare popularity with different audio features.
Analyze explicit vs. non-explicit tracks.
Visualize streaming distribution across countries.
Create an easy-to-understand interactive dashboard using Power BI.

📂 Dataset

Dataset: Spotify Artist Streaming Analytics 2020–2025

Source: Kaggle

The dataset contains information about Spotify tracks, artists, genres, release dates, streaming counts, popularity, and audio characteristics.

Important attributes
Track ID
Track Name
Artist Name
Album Name
Release Date
Genre
Duration Minutes
Popularity
Danceability
Energy
Key
Loudness
Mode
Instrumentalness
Tempo
Stream Count
Country
Explicit
Label
Release Year
Release Month
Release Day of Week
Release Quarter
Is Weekend Release
Artist Track Count

🧹 Data Preprocessing

The dataset was initially cleaned and prepared using Microsoft Excel.

The preprocessing steps included:

Selecting the required records for analysis.
Removing duplicate and unnecessary columns.
Checking and handling missing values.
Correcting data types.
Standardizing artist, track, album, and genre names.
Verifying release-date information.
Creating release year, month, and quarter information.
Checking numerical fields such as popularity, energy, danceability, tempo, and stream count.
Removing duplicate popularity fields.
Validating derived columns before using them in Power BI.

📊 Power BI Dashboard

The dashboard is divided into three main pages.

1. Spotify Overview

The first page provides an overall summary of the dataset.

KPI Cards
Total Tracks
Total Artists
Total Streams
Average Popularity
Average Energy
Visualizations
Top 10 Artists by Stream Count
Top 10 Tracks by Stream Count
Explicit vs Non-Explicit Tracks
Streams by Genre
Streams by Country

This page provides a quick overview of the overall Spotify dataset.

2. Release Analysis

The second page focuses on when music is released.

Visualizations
Tracks Released by Year — Line Chart
Tracks Released by Month — Column Chart
Tracks Released by Quarter — Column Chart
Tracks Released by Day of Week — Column Chart
Weekend vs Weekday Releases — Donut Chart
Release Trends by Genre — Line Chart

Analysis

This page helps identify:

Changes in music releases over the years.
Months with higher numbers of releases.
Quarterly release patterns.
Differences between weekday and weekend releases.
How release activity varies between genres.

3. Audio Analysis

The third page focuses on the audio characteristics of tracks.

KPI Cards
Average Popularity
Average Danceability
Average Energy
Average Tempo
Visualizations
Average Danceability by Genre
Average Energy by Genre
Popularity vs Danceability
Popularity vs Energy
Average Instrumentalness by Genre

Analysis

This page helps explore relationships between:

Popularity and danceability.
Popularity and energy.
Different audio characteristics across genres.
Tempo differences between genres.
Instrumentalness and loudness patterns.
🛠️ Tools Used
Microsoft Excel

Used for:

Data cleaning
Data preprocessing
Removing duplicates
Data validation
Preparing the dataset for visualization
Microsoft Power BI

Used for:

Data visualization
Dashboard development
KPI cards
Charts
Maps
Interactive filtering
Data analysis
DAX

Used for creating measures such as:

Total Streams = SUM('Spotify'[Stream Count])

Total Tracks = DISTINCTCOUNT('Spotify'[Track ID])

Total Artists = DISTINCTCOUNT('Spotify'[Artist Name])

Average Popularity = AVERAGE('Spotify'[Popularity])

Average Energy = AVERAGE('Spotify'[Energy])

Average Danceability = AVERAGE('Spotify'[Danceability])

Average Tempo = AVERAGE('Spotify'[Tempo])

🔄 Project Workflow

Raw Spotify Dataset
        ↓
Data Cleaning in Excel
        ↓
Data Validation
        ↓
Data Transformation
        ↓
Import into Power BI
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Dashboard Design
        ↓
Data Visualization
        ↓
Insights and Analysis

🎨 Dashboard Design

The dashboard follows a Spotify-inspired visual theme using:

Dark green
Spotify green
Black
White
Light green

The design includes:

Consistent navigation
KPI cards
Rounded visualization panels
Music-themed images
Green data visualizations
Clean typography
Consistent page layout

📈 Key Insights

The dashboard can be used to identify:

Which artists receive the highest streaming counts.
Which tracks achieve the highest streams.
Which genres have the highest streaming activity.
How music releases vary over time.
Which months and quarters have greater release activity.
Whether releases are more common on weekdays or weekends.
How danceability and energy relate to popularity.
How audio characteristics differ across genres.
How streaming activity varies geographically.

📁 Project Structure

Spotify-Artist-Streaming-Analytics/
│
├── Dataset/
│   └── spotify_cleaned.xlsx
│
├── PowerBI/
│   └── spotify_analytics_dashboard.pbix
│
├── Documentation/
│   └── Project_Report.pdf
│
└── README.md

👩‍💻 Project Type

Mini Project — Data Analytics & Visualization

Tools: Microsoft Excel, Microsoft Power BI, DAX

Domain: Music Analytics / Data Visualization

Dataset Source: Kaggle

📌 Conclusion

Spotify Artist Streaming Analytics demonstrates how raw music data can be transformed into meaningful visual insights using Excel and Power BI. The project combines data preprocessing, analytical measures, and interactive visualizations to understand artist performance, streaming trends, release patterns, and audio characteristics.

The resulting dashboard provides a clear and visually engaging way to explore the factors and patterns associated with Spotify music performance.
