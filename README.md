# Telegram Weather Bot

## Introduction
Welcome to the Telegram Weather Bot! This bot provides weather forecasts for locations around the world right in your Telegram chat. With its friendly personality and accurate weather predictions, it's your perfect companion for staying informed about the weather conditions.

## Features
- **Weather Forecast:** Get real-time weather updates including temperature, humidity, and wind speed for any city or town.
- **Personality Injection:** The bot injects a dash of personality into its responses to make interactions more engaging and enjoyable.
- **Error Handling:** Handles invalid input gracefully and provides helpful messages to guide users through the interaction process.

## Installation
### Prerequisites
- Python 3.x installed on your system.
- Telegram Bot API token. You can obtain one by creating a bot using the BotFather on Telegram.
- OpenWeatherMap API token. You can sign up for a free account on the OpenWeatherMap website to get your API key.
- OpenRouter API key. Sign up for an account on the OpenRouter website to obtain your API key.

### Usage
To interact with the Telegram Weather Bot, simply open a chat with the bot on Telegram and use the following commands:
- **/start:** Initiates a conversation with the bot and displays a welcome message.
- **/help:** Provides assistance and guidance on how to use the bot.
- **/weather:** Prompts you to enter a location for which you want to receive the weather forecast.

## How It Works
The Telegram Weather Bot uses the following technologies and APIs:
- **pyTelegramBotAPI:** Python library for interacting with the Telegram Bot API.
- **OpenWeatherMap API:** Provides weather data for any location worldwide.
- **OpenRouter API Integration:** Interfaces with OpenAI's GPT-3.5 model for injecting personality into bot responses.

When a user requests weather information for a specific location, the bot sends a request to the OpenWeatherMap API to fetch the relevant weather data. It then processes the data and sends back a weather forecast along with some injected personality to make the interaction more enjoyable.

### OpenRouter API Integration
The bot leverages the power of OpenRouter.ai to enhance its functionality:
- **Generating Responses:** The LLM AI can generate responses with human-like fluency and coherence, making interactions with the bot more natural and engaging.
- **Handling Queries:** The bot can utilize the LLM AI to handle complex user queries, providing accurate and informative responses tailored to the user's needs.
- **Adding Interaction Layer:** Integrating OpenRouter.ai adds another layer of interaction to the bot, allowing it to understand user inputs better and respond intelligently.
