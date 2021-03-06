# Slack PlantUML Bot

## Latest integration

- [![wercker status](https://app.wercker.com/status/27abe6c106f3a6a6e2b042e8db12c59f/s/ "wercker status")](https://app.wercker.com/project/byKey/27abe6c106f3a6a6e2b042e8db12c59f)
- [![CircleCI](https://circleci.com/gh/kazuhito-m/slack-plantuml-bot.svg?style=svg)](https://circleci.com/gh/kazuhito-m/slack-plantuml-bot)

## What's this

Slack上でPlantUMLの記述を行えば画像を返してくれるボット。

## Usage

### npm build & node run

```bash
# build
npm install && npm run build
# execute
SLACK_BOT_TOKEN=[your slack bot token] node ./build/bunld.js
```

### Docker image build & run container

```bash
# build
npm run docker-builds
# execute
docker run -d --restart=on-failure -e SLACK_BOT_TOKEN=[your slack bot token] kazuhito/slack-plantuml-bot
```

## 参考

[こちら](./doc/REFERENCE_PUBS.md)

## Author

+ [kazuhito_m](https://twitter.com/kazuhito_m)