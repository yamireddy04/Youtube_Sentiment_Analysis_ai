
##  YouTube Sentiment Analysis Using AI

This project analyzes the sentiment of YouTube video comments using artificial intelligence. It includes both a backend (for processing sentiment using machine learning) and a frontend (for displaying results to users).

 #  Project Structure

```
Youtube_Sentiment_Analysis_AI/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── db.sql
│   ├── models/
│   └── utils/
│
├── frontend/
│   ├── index.html
│   ├── styles/
│   ├── script.js
│   └── assets/
│
├── README.md
└── .gitignore
```

##  Features

* Fetches comments from YouTube videos using the YouTube Data API.
* Analyzes comment sentiment using an AI/ML model.
* Displays sentiment statistics (Positive, Negative, Neutral).
* Clean and interactive frontend interface.
* Stores analyzed data in a database.

##  Technologies Used

###  Backend

* Python
* Flask (or FastAPI)
* SQL (SQLite/MySQL)
* TextBlob / NLTK / Transformer Models for sentiment
* YouTube Data API

###  Frontend

* HTML, CSS, JavaScript
* Chart.js or other charting libraries

##  Setup Instructions

###  Backend Setup

1. Navigate to the backend folder:**

   ```bash
   cd backend
   ```

2. Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate     # Windows
   ```

3. Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:**
   Create a `.env` file and include your API keys:

   ```
   YOUTUBE_API_KEY=your_api_key_here
   ```

5. **Run the server:**

   ```bash
   python app.py
   ```

### Frontend Setup

1. Navigate to the frontend folder:**

   ```bash
   cd frontend
   ```
2. If using a build tool (optional):**

   * For React: `npm install` then `npm start`
   * For static HTML/JS/CSS: Just open `index.html` in a browser

##  Sample YouTube Link Used

* [https://www.youtube.com/watch?v=9yJWo7jafv4\&list=PLpLRk365gbPb1TnZNvDIuXP3tDeIcu8kB](https://www.youtube.com/watch?v=9yJWo7jafv4&list=PLpLRk365gbPb1TnZNvDIuXP3tDeIcu8kB)

## Example Output

* Bar charts or pie charts showing sentiment distribution.
* Table of comments with corresponding sentiment labels.

##  Future Improvements

* Add user authentication.
* Support for video title and channel name display.
* Use transformer-based sentiment models (like BERT).
* Enable download of analyzed data.


Before runing this project, we need to replace the yutube API key with your browser's youtube API v3 key
