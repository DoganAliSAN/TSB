
# Python Tiktok Scraping Bot (TSB)

TSB will get videos from tiktok tag you specified and send you videos from telegram with a txt file.
## Installation
First download files from github page.
Inside TSB folder do `pip3 install -r requirements.txt` .
This will install all the modules TSB needs

To learn more about how to install TSB please check this video
https://www.youtube.com/watch?v=KjSXLouS5Is

## Usage

```python
sudo python3 main.py
```

Open Telegram app and go to TSB bot 

<img src="s.png" data-canonical-src="s.png" width="300" height="500" />

Press start button 

<img src="start.png" data-canonical-src="s.png" width="300" height="500" />


you can type `/help` to learn how to use TSB

<img src="help.png" data-canonical-src="s.png" width="300" height="500" />


`/url` command gets two parameters, first for how many videos user wants, 
second for which tag TSB should look. This will take long time and return a text file to user.

`/settings` commands is for setting number of likes and comment. TSB will look for videos which has equal or higher values.

