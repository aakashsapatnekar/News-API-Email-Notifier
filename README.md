# News API Email Notifier

A simple Python automation tool that fetches real-time news articles from the NewsAPI and emails a formatted digest straight to your inbox.

## Features

- Retrieves real-time, keyword-filtered news articles using the NewsAPI REST API
- Sorts results by publish date to surface the latest articles first
- Parses article titles and descriptions from the JSON response
- Sends a formatted, UTF-8 encoded email digest via Gmail's SMTP server
- Modular design with separate modules for data retrieval and email delivery

## Tech Stack

- Python 3
- `requests` – for making HTTP calls to the NewsAPI
- `smtplib` / `ssl` – for secure email delivery over Gmail's SMTP server
- 
