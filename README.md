<p align="center">
  <img src="https://raw.githubusercontent.com/BigDaddyAman/KakiFilem-IMDb-Telegram-Bot/main/assets/logo.png" width="120" alt="KakiFilem IMDb Bot Logo">
</p>

<h1 align="center">🎬 KakiFilem IMDb Bot</h1>

<p align="center">
  Fast IMDb movie & TV search bot for Telegram.
</p>

<p align="center">
  <a href="https://t.me/KakiFilemIMDbBot">
    <img src="https://img.shields.io/badge/Telegram-Bot-2CA5E0?style=for-the-badge&logo=telegram">
  </a>

  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python">

  <img src="https://img.shields.io/badge/Aiogram-3.x-2CA5E0?style=for-the-badge&logo=telegram">

  <img src="https://img.shields.io/badge/PostgreSQL-16-336791?style=for-the-badge&logo=postgresql">

  <img src="https://img.shields.io/badge/Redis-Cache-red?style=for-the-badge&logo=redis">

  <img src="https://img.shields.io/badge/Status-Online-success?style=for-the-badge">
</p>

---

## ✨ Features

- ⚡ Fast inline movie search
- ⭐ IMDb ratings & votes
- 🎬 Trailer links
- 🖼 Movie posters & thumbnails
- 📺 TV series support
- 🚀 Redis caching
- 🗄 PostgreSQL persistence
- ☁️ Cloudflare + Caddy powered
- 🔥 Async Python architecture

---

## 🤖 Telegram Bot

Use the bot directly inside any Telegram chat:

```text
@KakiFilemIMDbBot interstellar
```

### Demo Bot
👉 https://t.me/KakiFilemIMDbBot

---

## 🏗 Architecture

```text
Cloudflare
     ↓
Caddy Reverse Proxy
     ↓
Aiogram + aiohttp Webhook
     ↓
Redis Cache + PostgreSQL
```

---

## ⚙️ Tech Stack

- Python
- Aiogram 3
- aiohttp
- PostgreSQL
- Redis
- uvloop
- orjson
- Docker

---

## 🚀 Performance

The bot is optimized for high-speed inline responses using:

- Shared aiohttp sessions
- Redis compressed caching
- PostgreSQL connection pooling
- Async concurrent fetching
- uvloop event loop acceleration

---

## 🔒 Privacy

Privacy Policy:
👉 https://imdb.kakifilem.com/privacy

---

## 📡 Infrastructure

Hosted on:
- Debian Linux
- Cloudflare
- Caddy Server
- PostgreSQL
- Redis

---

## 📌 Status

```text
Production Ready
```

---

## 📜 Source Code

This project is currently closed-source.

---

## ❤️ Support

If you enjoy using the bot, consider sharing it with friends and movie lovers.

---

## ⚠️ Disclaimer

This project is not affiliated with IMDb or Amazon.

All movie data, posters, ratings, and trademarks belong to their respective owners.
