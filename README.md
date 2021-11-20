# SurflineTelegramBot
Telegram bot for Surfline surf forecast updates 

A [Telethon](https://github.com/LonamiWebs/Telethon) bot that allows users to register daily surf forecasting updates for a specific spot, retrieved from [surfline.com](https://www.surfline.com/)'s api. You can set a minimum surf height that triggers the notifications.

* install dependencies `pip install -r requirements.txt`
* [register](https://core.telegram.org/api/obtaining_api_id) the bot and set the api id, api hash, and bot token in `.env` (see `env_sample`)
* run the bot `python app.py` 
