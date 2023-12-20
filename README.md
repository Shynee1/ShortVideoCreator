# Tiktok Video Creator
Python application to automate the creation of Reddit storytime posts. \
Manages everything from scraping the Reddit post to composing the final video. 

! [alt text](https://github.com/Shynee1/tiktokvideocreator/example.gif "Example")

## **Features**
- Scrapes the top post from popular subreddit 'AITA'
- Reads the post using Tiktok's text-to-speech API
- Converts TTS to timestamped subtitles using OpenAI's 'Whisper'
- Adds background audio/video and composes final result with MoviePy
  
## **Documentation**
- Download project files (code -> download ZIP)
- Download required [background gameplay files](https://drive.google.com/drive/folders/1TWEpfcW3aq6tcTMpgAP9RhPVDR6HpWza?usp=sharing)
- Add `background_videos` to project's `assets` folder
- Create [Reddit Developer Application](https://old.reddit.com/prefs/apps/)
- Add Reddit credentials to `praw.ini`
- Run `main.py`
