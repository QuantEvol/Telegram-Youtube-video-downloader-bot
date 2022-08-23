# Telegram bot to download audio and video from youtube
Using the python API this BOT will download a video or audio of the link that is sent to the bot, if the file size is less than 50MB, the bot will send it to you.

## Install requirements:
#### `sudo apt install ffmpeg`
#### `pip install pytube`

## Instrucions:
#### Create a new telegram bot https://telegram.me/BotFather
#### Choose a name for your bot and copy the "token"
#### Paste the token in the line 146 of the "telegram-pytube", for example:
#### `base_url = 'https://api.telegram.org/bot270485614:AAHfiqksKZ8WmR2zSjiQ7_v4TMAKdiHm9T0'`
## Run the script:
#### `python telegram-pytube.py`
#### If the audio or video file size is less than 50MB (telegram api limitation) it will be send to you.
