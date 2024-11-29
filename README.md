# File uploader/subreddit media sender to Discord webhook 
This script runs a backend launching a website that allows you to upload anything to discord via a webhook and automates reddit sending to the Discord webhook, all you need to do is type the subreddit name.

## Requirements 
- pip installations in the requirements.txt
- Python 3.8.x+ (use ``py --version`` to check)

## How to use 
1. Open your command line
2. Use ``cd ...the directory folder...``
3. Run ``pip install -r requirements.txt``
4. Once complete, fill in your .env using [this](https://www.reddit.com/prefs/apps)
5. Choose the script use as an option and return to stage 4 until .env is fullfilled
6. Use either ``py backend.py`` or ``python backend.py`` to start the backend
7. In the terminal it will give you two websites to visit and you will use that (the frontend)

## Issues
Contact me via ``support@starlover.online`` in a case of any issues with an image and explanation

Note: for reddit use, it sends titles and descriptions if there is no picture/gif media available (and with), buttons to view posts and there is no suppport for videos from reddit yet **yet**, everything on upload is supported.
