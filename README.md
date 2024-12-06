# File uploader/subreddit media sender to Discord webhook 
This script sets up a backend service that launches a website. The website allows users to upload files to Discord using a webhook. Also, it automates the process of sending posts from specified subreddits to the Discord webhook. The users simply need to enter the name of the subreddit.

## Requirements 
- pip installations in the requirements.txt
- Python 3.8.x+ (use ``python --version`` to check)

## How to use 
1. Open your command line
2. Use ``cd ...the directory folder...``
3. Run ``pip install -r requirements.txt``
4. Once complete, fill in your .env using [this](https://www.reddit.com/prefs/apps)
5. Choose the script use as an option and return to stage 4 until .env is fullfilled
6. Use ``python backend.py`` to start the backend
7. In the terminal it will give you two websites to visit and you will use that (the frontend)

## Issues
Contact me via <a href="mailto:support@starlover.online">support@starlover.online</a> in a case of any issues with an image and explanation

**Note:** For Reddit usage, the script sends titles and descriptions if no picture or GIF media is available. It includes buttons to view posts. Currently, there is no support for videos from Reddit. All types of uploads are supported.
