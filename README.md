# Simple URL Shortener

This project is a backend URL shortener built using Flask and SQLite as part of the CodeAlpha Backend Development Internship.

## Features
- Shorten long URLs
- Redirect short URLs to original URLs
- Uses SQLite database

## How to Run
1. Install dependencies  
   pip install -r requirements.txt

2. Run the app  
   python app.py

## API Endpoints
- POST /shorten  
  Request Body:
  {
    "url": "https://example.com"
  }

- GET /<short_code>  
  Redirects to original URL
