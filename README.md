# ModStation 🛡️

**Рабочее место модератора Twitch.** Чат в реальном времени, автомодерация,
пользователи, логи и статистика — в одном дашборде в фиолетовом неоне Twitch.

![license](https://img.shields.io/badge/license-MIT-purple?style=flat-square)
![twitch](https://img.shields.io/badge/twitch-API-9146FF?style=flat-square)

![ModStation](docs/screenshots/hero.png)

## ✨ Возможности

- 💬 **Чат** — модерация в реальном времени: читай и отправляй сообщения, лови нарушителей
- 🛡 **Фильтры** — автомодерация: спам, ссылки, запрещённые слова — сообщение подсвечивается, спамер помечается
- 👥 **Пользователи** — таймауты и баны без переключения вкладок
- 📊 **Дашборд** — статистика и активность канала
- 📜 **Логи** — история действий модерации
- 🔐 **Вход через Twitch** — OAuth, без паролей в приложении

## 🚀 Быстрый старт

```bash
git clone https://github.com/USERNAME/modstation.git
cd modstation
cp .env.example .env   # впиши TWITCH_CLIENT_ID / TWITCH_CLIENT_SECRET
npm install
npm run dev
```

## 🔑 Ключи Twitch

1. Зайди на [dev.twitch.tv/console](https://dev.twitch.tv/console)
2. Создай приложение → Redirect URL: `http://localhost:3000/callback`
3. Скопируй Client ID и Secret в `.env`

## 📄 Лицензия

[MIT](LICENSE)
