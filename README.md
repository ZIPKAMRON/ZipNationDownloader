# YouTube Downloader

**An Inline Telegram bot that can download YouTube videos with permanent thumbnail support**

<br>

  - Bot need to be in Inline Mode
  - Search keyword inline (In bot chat).
  - Send a photo to bot to set custom thumbnail permanently.
  - The thumbnail will be in all the downloads until clear it in options.
  - View the custom thumbnail in option.
  - If no thumbnail available, bot will set the default YouTube video thumbnail in downloading.
  - If Authorized users are available, bot will serve to them only. If not, bot will be in public domain.

<br>

<p align="left">
  <a href="https://heroku.com/deploy?template=https://github.com/Rexinazor/Youtube_Downloader">
     <img height="30px" src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku">
  </a>
</p>

## Mandatory Variables

* `API_HASH`    Your API Hash from my.telegram.org
* `API_ID`      Your API ID from my.telegram.org
* `BOT_TOKEN`   Your bot token from @BotFather
* `AUTH_USERS`  Create a list of User Ids to use this bot

## Deploy Locally

Create a `config.py` with the above variables (Refer sample_config.py)
```
git clone https://github.com/Rexinazor/Youtube_Downloader
cd Youtube_Downloader
virtualenv -p python3 venv
. ./venv/bin/activate
pip3 install -r requirements.txt
python3 bot.py
```



