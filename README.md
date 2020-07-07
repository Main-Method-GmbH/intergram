# Description
Docker Image for integrating self hosted Live Chat on your website with Telegram and intergram. Credits go to https://github.com/idoco/intergram

# Usage

1. Open Telegram and type @BotFather
2. Create a new bot with `/newbot`
3. Use the API Token as environment variable TELEGRAM_TOKEN in the docker run command below

## Use our Docker Image
`docker run -d -p 80:3000 -e TELEGRAM_TOKEN="Your Token" mainmethod/intergram`

## Build on your own
`docker build -t mainmethod/intergram .`
