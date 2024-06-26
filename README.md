## Discord TA Bot

A bot to help answer students' questions 24/7. 

Using the pycord library: 

`pip install [git+https://github.com/Pycord-Development/pycord](git+https://github.com/Pycord-Development/pycord)`

This project is a Discord bot that uses OpenAI's GPT-3 model to interact with users in a Discord server. The bot is designed to answer questions or comments from users, and it can also create and manage threads in Discord.

### Features
Thread Naming: The bot can create a new thread based on a user's question or comment. It uses the GPT-3 model to generate a descriptive name for the thread.

Message History: The bot can recall the history of a thread and use it to generate more accurate and context-aware responses.

Character Limit: The bot ensures that its responses do not exceed Discord's character limit of 2000 characters.

Role Playing: The bot is designed to play the role of a Makecode Python expert and a high school computer science teacher, making it ideal for educational servers.

### How it Works
The bot uses several Python libraries and modules to interact with the Discord API and the OpenAI API. Here's a brief overview of how it works:

1. The bot listens for messages in which it is mentioned.
2. If the bot is mentioned in a thread, it retrieves the history of the thread and uses it to generate a response.
3. If the bot is mentioned outside of a thread, it creates a new thread with a name generated by the GPT-3 model based on the user's message.
4. The bot sends its response in the appropriate thread.

### Setup
To use this bot, you need to have Python installed on your machine and you need to set up a bot on the Discord Developer Portal. You also need to have an API key from OpenAI.

1. Clone this repository to your local machine.
2. Install the required Python libraries using pip.
3. Set up a .env file with your Discord bot token and OpenAI API key.
4. Run the bot script.

### Usage
To interact with the bot, simply mention it in a message on your Discord server. The bot will either respond in the thread where it was mentioned or create a new thread if it was mentioned outside of a thread.

![alt text](./project_discord_bot.png)

### Note
This bot is designed to be used in educational settings. It should not be used to share sensitive information or to perform tasks that require a high level of security.
