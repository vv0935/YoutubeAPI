# YoutubeAPI
This project demonstrates how to use the YouTube Data API to extract and analyze data from YouTube channels and videos. It includes data extraction, analysis, and visualization of channel and video metrics. The project is implemented in Python and utilizes libraries like google-api-python-client, pandas, and seaborn.

Features
Channel Data Extraction:

Extracts channel details such as:
Channel Name
Total Subscribers
Total Views
Total Number of Videos
Compares data across channels and visualizes metrics using Seaborn.
Video Data Extraction:

Fetches details like:
Video Title
Published Date
Views, Likes, Comments, etc.
Loads the data into a pandas DataFrame for analysis.
Visualizes trends and patterns using Seaborn.
Visualization:

Compares metrics (e.g., views, subscribers) between channels.
Analyzes video performance.
Extracted Channel Details
The project compares the following YouTube channels:

T-Series Telugu
Netflix India
Mythri Movie Makers
Prime Video India
Sony Music South
Installation
Prerequisites
Python 3.8 or above
Jupyter Notebook
Anaconda (optional, for creating a virtual environment)
Setup Instructions
Clone the Repository:

bash
Copy code
git clone https://github.com/<your-username>/youtube-data-analysis.git
cd youtube-data-analysis
Create a Virtual Environment:

bash
Copy code
conda create -n youtube_api_env python=3.8
conda activate youtube_api_env
Install Required Packages:

bash
Copy code
pip install google-api-python-client pandas seaborn
Generate YouTube API Key:

Follow Google's API Documentation to generate an API Key.
Enable the YouTube Data API v3 in your project.
How to Run
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook
Load the provided Python scripts to:

Extract and analyze channel details.
Extract and analyze video details.
Visualizations are auto-generated in the notebook using Seaborn.

Project Structure
bash
Copy code
youtube-data-analysis/
│
├── data/                     # Folder for storing extracted data (optional)
├── visualizations/           # Folder for saving generated visualizations
├── scripts/                  # Python scripts for data extraction and analysis
│   ├── extract_channels.py
│   ├── extract_videos.py
│   └── visualize_data.py
├── README.md                 # Project README
└── requirements.txt          # Python dependencies
Implementation Steps
Part 1: Channel Analysis
Extracted channel details:
Subscribers, Views, and Total Videos.
Loaded data into a pandas DataFrame for analysis.
Visualized and compared the data using Seaborn.
Part 2: Video Analysis
Extracted video details from selected channels:
Video Title, Views, Likes, Comments, etc.
Loaded video data into a pandas DataFrame.
Visualized video performance metrics.
Sample Visualizations
Channel Metrics Comparison: Bar charts comparing subscriber counts, views, and video counts.
Video Performance: Scatter plots showing views vs. likes, comments vs. views, etc.
Acknowledgments
This project is inspired by a YouTube video tutorial for beginners in data analysis. It is intended as a starting point for aspiring data analysts to learn API integration, data analysis, and visualization.

Future Enhancements
Add support for additional YouTube API features like playlists and comments analysis.
Include advanced visualizations using libraries like Plotly or Matplotlib.
Optimize API usage for large-scale data extraction.
