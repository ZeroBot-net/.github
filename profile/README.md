<h1 align="center">ZeroBot.net</h1>

<p align="center">
  <b>Bot hosting and bot-building platform.</b><br>
  Run your Telegram, Discord and web bots (Node.js, Python, Go, PHP) on fast servers, with open-source tools to build them.
</p>

<p align="center">
  <a href="https://zero-bot.net">Website</a> ·
  <a href="https://www.npmjs.com/package/@zero-bot.net/tg-bot-api">npm: tg-bot-api</a> ·
  <a href="https://zerobot-net.github.io/tg-bot-api/">Docs</a>
</p>

## What is ZeroBot.net?

[ZeroBot.net](https://zero-bot.net) is a **bot hosting platform**: you rent a server, upload your bot, and keep it online 24/7 from a web panel. Pay and manage your servers in one place, and run Node.js, Python, Go or PHP bots without managing your own VPS.

We also build and publish the **open-source libraries and bots** we use ourselves.

## Open-source projects

| Project | What it is | Install |
|---|---|---|
| [**tg-bot-api**](https://github.com/ZeroBot-net/tg-bot-api) | Lightweight **Telegram Bot API** library for Node.js. Full Bot API 10.3 coverage (203 methods), polling and webhooks, TypeScript types, no build step. [Docs](https://zerobot-net.github.io/tg-bot-api/) | `npm i @zero-bot.net/tg-bot-api` |
| [**TG-StoreBot-fastest**](https://github.com/ZeroBot-net/TG-StoreBot-fastest) | Fast **Telegram file store bot**: private channel as storage, 10-digit deep links, multi-channel backup, TTL auto-expire. Python, aiogram, SQLite. | `uv sync` |
| [**request**](https://github.com/ZeroBot-net/request) | Maintained fork of the Node.js `request` **HTTP client**. | `npm i @zero-bot.net/request` |

## Quick start: a Telegram bot in Node.js

```js
const TelegramBot = require('@zero-bot.net/tg-bot-api');

const bot = new TelegramBot('YOUR_BOT_TOKEN', { polling: true });
bot.on('message', (msg) => bot.sendMessage(msg.chat.id, 'Hello from ZeroBot!'));
```

Then host it on [zero-bot.net](https://zero-bot.net).

## Topics

`bot hosting` · `telegram bot` · `telegram bot api` · `nodejs` · `python` · `discord bot hosting` · `game server hosting` · `file store bot`

## Contributing

Issues and pull requests are welcome in each repository. Please read the repo's `CONTRIBUTING.md` first where one exists.
