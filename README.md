# Verbot

A web-based chatbot application built using Flask and ChatterBot. This project demonstrates how to integrate a conversational AI chatbot into a web interface.

## Description

This project is a simple implementation of a chatbot application using Flask (a Python web framework) and ChatterBot (a machine learning based conversational AI). The application allows users to chat with a bot that can respond to messages based on predefined training data.

## Features

- Web-based chat interface
- Message history display
- Responsive design
- Pre-trained chatbot model
- Simple and clean UI

## Requirements

- Python 3.6+
- Flask
- ChatterBot
- ChatterBot Corpus

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sorna-das-sdp2.git
   
2. Install the required dependencies:
   ```bash
    pip install -r requirements.txt

3. Run the application:
  ```bash
     python app.py
```
4. Running the Application
  ```bash
      After installing the dependencies and running the application, open your web browser and navigate to http://localhost:5000. You should see the chat interface where you can start chatting with the bot.
```
5. Directory Structure
  ``` bash
  sorna-das-verbot/
  ├── README.md          # Project documentation
  ├── app.py             # Flask application
  ├── db.sqlite3         # Database file for ChatterBot
  ├── requirements.txt   # Dependencies list
  ├── sentence_tokenizer.pickle
  ├── static/            # CSS and other static files
  │   └── style.css      # Styling for the web interface
  └── templates/         # HTML templates
      └── index.html     # Main web page

```
