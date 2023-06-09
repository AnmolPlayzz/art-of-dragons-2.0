# Art of Dragons Discord Bot

Art of Dragons is an open-source Discord bot made using Discord.js v14. It is designed to bring fun and utility to your Discord server.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Features

- **/help**: Get a list of available commands and their descriptions.
- **/ping**: Check the bot's latency and responsiveness.
- **/stats**: View statistics about the bot, such as uptime and server count.

The bot is a work in progress, and more features are being added regularly.

Apologies for the oversight. Here's the updated version including the intents step and instructions on how to invite the bot:

## Installation

To run the Art of Dragons Discord bot on your own server, follow these steps:

1. Clone the repository:

    ```
    git clone https://github.com/your-username/art-of-dragons.git
    ```

2. Install the required dependencies:

    ```
    npm install
    ```

3. Create a new Discord application and bot on the Discord Developer Portal. Here's how:

   - Visit the [Discord Developer Portal](https://discord.com/developers) and log in with your Discord account.
   - Click on the "New Application" button located at the top right corner of the Developer Portal. This will create a new application that will serve as the foundation for your Discord bot.
   - Enter a name for your application in the provided field. You can choose any name that represents your bot, such as "Art of Dragons Bot."
   - Once you have entered a name, click on the "Create" button to create your application. You will be redirected to the application's settings page.
   - In the left sidebar of the application settings page, locate and select the "Bot" tab. This tab contains settings specifically related to your bot.
   - Click on the "Add Bot" button to create a bot for your application. This will enable you to assign a unique bot token to your bot, which is necessary for it to connect to Discord's API.
   - Customize your bot's settings based on your preferences, such as its username and profile picture. You can also configure other settings as desired.
   - Under the "Token" section on the bot settings page, you will find your bot's token. Click on the "Copy" button next to the token to copy it to your clipboard.
   - Scroll down to the "Privileged Gateway Intents" section and enable both the "Presence Intent" and "Server Members Intent" options. These intents are required for certain functionalities, such as tracking member updates and presence information.
   - After enabling the intents, click on the "Save Changes" button to apply the modifications.

4. Once you have obtained the bot token and enabled the intents, go to the cloned repository of the bot on your local machine and locate the `.env.example` file. Open it using a text editor.

5. Replace the placeholder values for `TOKEN` and `CLIENTID` with the bot token and clientID (from the Developer Portal). Replace the values for `GUILDID` and `BOTLOG` with your serverID and channelID for bot logs.

6. Save the file and rename it to just `.env` (remove the `.example` extension).

7. Your bot is now ready to be started. To start the bot, run the following command:

    ```
    node index.js
    ```

Make sure you have Node.js (v16 or higher) and npm installed on your machine.

## Usage

To use the Art of Dragons Discord bot, you need to invite it to your server. Here's how:

1. Visit the [Discord Developer Portal](https://discord.com/developers) and navigate to your bot's application settings.
2. In the left sidebar, select the "OAuth2" tab.
3. Then select "URL Generator" from the submenu.
4. Upder "scopes" select "Bot" & "Application.Commands"
4. In the "Bot Permissions" section, customize the permissions based on the features your bot requires. For example, if your bot needs the ability to send messages and read member information, enable the "Send Messages" and "Read Members" permissions.
5. After selecting the desired permissions, a generated URL will appear in the "Generated URL" section. Click on the "Copy" button next to the URL to copy it to your clipboard.
6. Open a web browser and paste the copied URL into the

## Contributing

Contributions to Art of Dragons are always welcome. If you have any ideas, bug reports, or feature requests, please open an issue on the GitHub repository.

To contribute code to the project, follow these steps:

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
3. Create a new branch for your changes: `git checkout -b my-new-feature`
4. Make your changes and commit them: `git commit -am 'Add new feature'`
5. Push your changes to your forked repository: `git push origin my-new-feature`
6. Submit a pull request on the GitHub repository.

Please ensure that your code adheres to the project's coding conventions and includes appropriate documentation where necessary.

## License

Art of Dragons is licensed under the [MIT License](LICENSE). Feel free to modify and distribute the code according to the terms of the license.