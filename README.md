## Usage

### With Docker

1. Get a telegram bot token from @botfather and paste it in docker-compose.yml
2. Run `docker-compose up -d`
3. Find logs in logs/log.log file

### Without Docker

1. Install node and npm
2. Run `npm i` to install node_modules
3. Run `export TELEGRAM_BOT_TOKEN=<your bot token here>` to add bot token to environment variable
4. Run `npm start` to start the bot
