# YouTube Video Finder with Analysis 

This project is part of my **AI Automation Internship Assignment**. It automatically searches YouTube for videos based on a user's query and uses a GPT-2 model to analyze the video titles and suggest the most relevant one.

## Features

-  Search YouTube using the YouTube Data API v3.
-  Collect video titles, channel names, and URLs.
-  Use GPT-2 to choose the best video title based on relevance.
-  Uses `.gitignore` to safely exclude secret API keys and other sensitive files.

## Technologies Used

- Python
- Jupyter Notebook
- Hugging Face Transformers (GPT-2)
- Google YouTube Data API v3
- PyTorch

## How It Works

1. User enters a search query.
2. The app fetches the top 5 YouTube video results.
3. Titles are sent as a prompt to the GPT-2 model.
4. GPT-2 responds with the number of the most relevant video.
5. The result is displayed with title, channel, and video link.

##  Security

Sensitive information like API keys are stored in `secrete.py` and **excluded from version control** using `.gitignore`.


