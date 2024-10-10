# Sui Discord Bot

## Description
This Discord bot provides real-time price updates and statistics for the Sui cryptocurrency. It fetches data from the CoinGecko API and displays it in an embedded message within a specified Discord channel. The bot also includes a command to quickly check the current Sui price.

## Features
- Real-time Sui price updates
- 24-hour, 7-day, and 30-day price change percentages
- Market cap and trading volume information
- Circulating supply details
- All-time high price and date
- Price history chart (last 30 days)
- Quick price check command

## Requirements
- Python 3.9+
- discord.py
- httpx
- matplotlib
- python-dotenv

## Setup
1. Clone this repository:
   ```
   git clone https://github.com/QuothingRaven/sui-discord-bot.git
   cd sui-discord-bot
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory and add your Discord bot token:
   ```
   DISCORD_BOT_TOKEN=your_bot_token_here
   ```

4. Update the `EMBED_CHANNEL_ID` in the script with your desired Discord channel ID.

5. Invite the bot to your Discord server with the necessary permissions.

## Usage
1. Run the bot:
   ```
   python bot.py
   ```

2. The bot will automatically update the Sui statistics in the specified channel every 30 minutes.

3. Use the `~price` command in any channel to get a quick update on the current Sui price.

## Commands
- `~price`: Displays the current price of Sui

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/sui-discord-bot/issues).

## License
This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

## Disclaimer
This bot is for informational purposes only. Do not use it to make investment decisions. Always do your own research before investing in cryptocurrencies.
