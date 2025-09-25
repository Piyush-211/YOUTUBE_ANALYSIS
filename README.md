# YouTube Comment Sentiment Analysis

A Python and Streamlit application to analyze YouTube video comments and visualize their sentiment. This project fetches comments from a YouTube video, performs sentiment analysis using **NLTK's VADER**, and displays the results in interactive charts using **Plotly**.

---

## Features

- Extract comments from YouTube videos using YouTube Data API v3.
- Analyze sentiment of comments (positive, negative, neutral) using VADER.
- Visualize sentiment distribution with bar and pie charts.
- Save comments and analysis to CSV for further analysis.
- Simple and interactive web interface with Streamlit.

---

## Technologies Used

- **Python 3.12**
- **Streamlit** – Web app framework
- **NLTK** – Natural Language Toolkit for sentiment analysis
- **Google API Client** – Fetch comments from YouTube
- **Plotly** – Interactive charts and visualizations
- **Pandas** – Data handling and CSV export

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Piyush-211/YOUTUBE_ANALYSIS.git
cd youtube-comment-sentimental-analysis
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # macOS/Linux
Install required packages:

bash
Copy code
pip install -r requirements.txt
If requirements.txt is not present, install manually:

bash
Copy code
pip install streamlit nltk plotly google-api-python-client pandas
Set your YouTube API key:

Create a .streamlit/secrets.toml file:

toml
Copy code
YOUTUBE_API_KEY = "YOUR_YOUTUBE_API_KEY"
Usage
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Enter a YouTube video URL in the app.

Fetch and analyze comments.

View sentiment charts and save results as CSV.

Folder Structure
bash
Copy code
youtube-comment-sentimental-analysis/
│
├─ app.py                 # Main Streamlit app
├─ Senti.py               # Sentiment analysis functions
├─ YoutubeCommentScrapper.py  # Fetch comments from YouTube
├─ requirements.txt       # Python dependencies
├─ .streamlit/secrets.toml # YouTube API key
└─ README.md

