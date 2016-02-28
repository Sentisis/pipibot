# Pipibot
_A Slack bot that works with Arduino to tell you if the bathroom is free_

Pipibot is a tool for big offices to save time by avoiding long trips to realize that the bathroom wasn't available. It uses an Arduino device with a photoresistor and a Wi-Fi module. The device saves the status of the bathroom so the Slack bot can check it when the user sends the request.

## Getting Started
1) Install the Botkit dependency

```
npm install
```

2) [Setup](https://my.slack.com/services/new/bot) the bot integration in your Slack channel. You will need the Token.

3) Run pipibot, using the token you just copied:

```
token=REPLACE_THIS_WITH_YOUR_TOKEN node pipibot.js
```

4) Invite pipibot to your channel: ``/invite @pipibot``. You can also send DM's.
