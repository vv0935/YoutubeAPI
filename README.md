
# YouTube Data Analysis Project

This project demonstrates how to use the YouTube Data API to extract and analyze data from YouTube channels and videos. It includes data extraction, analysis, and visualization of channel and video metrics. The project is implemented in Python and utilizes libraries like `google-api-python-client`, `pandas`, and `seaborn`.

---

## Features
1. **Channel Data Extraction**:
   - Extracts channel details such as:
     - Channel Name
     - Total Subscribers
     - Total Views
     - Total Number of Videos
   - Compares data across channels and visualizes metrics using Seaborn.

2. **Video Data Extraction**:
   - Fetches details like:
     - Video Title
     - Published Date
     - Views, Likes, Comments, etc.
   - Loads the data into a pandas DataFrame for analysis.
   - Visualizes trends and patterns using Seaborn.

3. **Visualization**:
   - Compares metrics (e.g., views, subscribers) between channels.
   - Analyzes video performance.

---

## Extracted Channel Details
The project compares the following YouTube channels:
1. **T-Series Telugu**
2. **Netflix India**
3. **Mythri Movie Makers**
4. **Prime Video India**
5. **Sony Music South**

---

## Installation

### Prerequisites
- Python 3.8 or above
- Jupyter Notebook
- Anaconda (optional, for creating a virtual environment)

### Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/youtube-data-analysis.git
   cd youtube-data-analysis
   ```

2. **Create a Virtual Environment**:
   ```bash
   conda create -n youtube_api_env python=3.8
   conda activate youtube_api_env
   ```

3. **Install Required Packages**:
   ```bash
   pip install google-api-python-client pandas seaborn
   ```

4. **Generate YouTube API Key**:
   - Follow [Google's API Documentation](https://developers.google.com/youtube/registering_an_application) to generate an API Key.
   - Enable the YouTube Data API v3 in your project.

---

## How to Run

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Load the provided Python scripts to:
   - Extract and analyze channel details.
   - Extract and analyze video details.

3. Visualizations are auto-generated in the notebook using Seaborn.

---

## Project Structure

```
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
```

---

## Implementation Steps

### Part 1: Channel Analysis
1. Extracted channel details:
   - Subscribers, Views, and Total Videos.
2. Loaded data into a pandas DataFrame for analysis.
3. Visualized and compared the data using Seaborn.

### Part 2: Video Analysis
1. Extracted video details from selected channels:
   - Video Title, Views, Likes, Comments, etc.
2. Loaded video data into a pandas DataFrame.
3. Visualized video performance metrics.

---

## Sample Visualizations

- **Channel Metrics Comparison**: Bar charts comparing subscriber counts, views, and video counts.
- **Video Performance**: Scatter plots showing views vs. likes, comments vs. views, etc.

---

## Acknowledgments

This project is inspired by a YouTube video tutorial for beginners in data analysis. It is intended as a starting point for aspiring data analysts to learn API integration, data analysis, and visualization.

---

## Future Enhancements
- Add support for additional YouTube API features like playlists and comments analysis.
- Include advanced visualizations using libraries like Plotly or Matplotlib.
- Optimize API usage for large-scale data extraction.
