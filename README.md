# Embedchain Telegram Bot Template

## Template Setup
- Fork this replit template.
- Set your `OPENAI_API_KEY` in Secrets.
- Open the Telegram app and search for the `BotFather` user.
- Start a chat with BotFather and use the `/newbot` command to create a new bot.
- Follow the instructions to choose a name and username for your bot.
- Once the bot is created, BotFather will provide you with a unique token for your bot.
- Set this token as `TELEGRAM_BOT_TOKEN` in Secrets.
- Click on `Run` in the replit container and a URL will get generated for your bot.
- Now set your webhook by running the following link in your browser:
```url
https://api.telegram.org/bot<Your_Bot_Token_Value>/setWebhook?url=<Replit_generated_URL>
```
- When you get a successful response in your browser, your bot is ready to be used.

## Usage Instructions
- Open your bot by searching for it using the bot name or bot username.
- Click on `Start` or type `/start` and follow the on screen instructions.