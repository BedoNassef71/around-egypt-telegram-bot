```markdown
# Around Egypt Telegram Bot

Around Egypt Telegram Bot is a Telegram bot built with TypeScript and Node.js that provides various features related to Egypt, such as weather information, currency conversion, football data, and landmarks information.

## Features

- **Weather**: Get the current weather conditions and forecasts for locations in Egypt.
- **Currency Conversion**: Convert between different currencies with real-time exchange rates.
- **Football Data**: Access football-related information such as standings, team details, and top scores for Egyptian football leagues.
- **Landmarks**: Explore famous landmarks and attractions in Egypt.

## Setup

1. Clone the repository:

```bash
git clone https://github.com/BedoNassef71/around-egypt-telegram-bot.git
```

2. Install dependencies:

```bash
cd around-egypt-telegram-bot
npm install
```

3. Set up environment variables:

   Create a `.env` file in the root directory and add the following variables:

   ```plaintext
   TELEGRAM_BOT_TOKEN=<your_telegram_bot_token>
   OPEN_WEATHER_MAP_API_KEY=<your_weather_api_key>
   COUNTRY_STATE_CITY_API_KEY=<your_country_state_city_api_key>
   CURRENCY_FREAKS_API_KEY=<your_currency_api_key>
   ALL_SPORTS_API_KEY=<your_football_api_key>
   LEAGUE_ID=141
   ```

   Replace `<your_telegram_bot_token>`, `<your_weather_api_key>`, `<your_country_state_city_api_key>`, and `<your_currency_api_key>`, and `<your_football_api_key>` with your actual API keys.

   - `TELEGRAM_BOT_TOKEN`: Token for authenticating with the Telegram Bot API.
   - `OPEN_WEATHER_MAP_API_KEY`: API key for accessing weather data from OpenWeatherMap.
   - `COUNTRY_STATE_CITY_API_KEY`: API key for accessing country, state, and city data.
   - `CURRENCY_FREAKS_API_KEY`: API key for accessing currency conversion data.
   - `ALL_SPORTS_API_KEY`: API key for accessing sports data.
   - `LEAGUE_ID`: ID of the football league.

4. Start the bot:

```bash
npm start
```

## Usage

- Start a conversation with the bot by searching for it on Telegram and clicking on "Start".
- Use the available commands to access different features related to Egypt:
  - `/weather`: Get weather information for locations in Egypt.
  - `/currency`: Convert currencies with real-time exchange rates.
  - `/football`: Access football data for Egyptian football leagues.
  - `/landmarks`: Explore famous landmarks and attractions in Egypt.

## Contributing

Contributions are welcome! If you have any ideas for new features, improvements, or bug fixes related to Egypt, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`.
3. Make your changes and commit them: `git commit -am 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.