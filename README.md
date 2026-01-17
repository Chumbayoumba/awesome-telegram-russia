<div align="center">

# 🤖 Awesome Telegram Russia

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Telegram](https://img.shields.io/badge/Telegram-@longfest-2CA5E0?logo=telegram&logoColor=white)](https://t.me/longfest)

**Курируемый список ресурсов для разработки Telegram-ботов и Mini Apps в России**

[English](#) | **Русский**

</div>

---

## 📚 Содержание

- [Библиотеки](#-библиотеки)
- [Mini Apps (TWA)](#-mini-apps-twa)
- [TON & Web3](#-ton--web3)
- [Хостинг и деплой](#-хостинг-и-деплой)
- [Приём платежей](#-приём-платежей)
- [Туториалы](#-туториалы)
- [Telegram-каналы](#-telegram-каналы)
- [Шаблоны и бойлерплейты](#-шаблоны-и-бойлерплейты)
- [Инструменты](#-инструменты)

---

## 📦 Библиотеки

### Python
| Название | Описание | Stars |
|----------|----------|-------|
| [aiogram](https://github.com/aiogram/aiogram) | Современный async фреймворк для Telegram Bot API | ![Stars](https://img.shields.io/github/stars/aiogram/aiogram?style=flat-square) |
| [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) | Обёртка для Telegram Bot API | ![Stars](https://img.shields.io/github/stars/python-telegram-bot/python-telegram-bot?style=flat-square) |
| [Telethon](https://github.com/LonamiWebs/Telethon) | Полный клиент Telegram API | ![Stars](https://img.shields.io/github/stars/LonamiWebs/Telethon?style=flat-square) |
| [Pyrogram](https://github.com/pyrogram/pyrogram) | MTProto клиент для Python | ![Stars](https://img.shields.io/github/stars/pyrogram/pyrogram?style=flat-square) |

### JavaScript / TypeScript
| Название | Описание | Stars |
|----------|----------|-------|
| [grammY](https://github.com/grammyjs/grammY) | Telegram Bot Framework для Deno/Node.js | ![Stars](https://img.shields.io/github/stars/grammyjs/grammY?style=flat-square) |
| [Telegraf](https://github.com/telegraf/telegraf) | Modern Telegram Bot Framework | ![Stars](https://img.shields.io/github/stars/telegraf/telegraf?style=flat-square) |
| [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | Node.js модуль для Telegram Bot API | ![Stars](https://img.shields.io/github/stars/yagop/node-telegram-bot-api?style=flat-square) |

### Другие языки
| Язык | Библиотека | Описание |
|------|------------|----------|
| Go | [telebot](https://github.com/tucnak/telebot) | Telegram Bot Framework для Go |
| Rust | [teloxide](https://github.com/teloxide/teloxide) | Элегантный фреймворк для ботов |
| PHP | [telegram-bot-sdk](https://github.com/irazasyed/telegram-bot-sdk) | SDK для Laravel/PHP |
| Java | [TelegramBots](https://github.com/rubenlagus/TelegramBots) | Java библиотека для ботов |

---

## 📱 Mini Apps (TWA)

### SDK и библиотеки
| Название | Описание |
|----------|----------|
| [@telegram-apps/sdk](https://github.com/Telegram-Mini-Apps/telegram-apps) | Официальный SDK для Mini Apps |
| [@tma.js/sdk](https://github.com/Telegram-Mini-Apps/tma.js) | TypeScript SDK для TWA |
| [telegram-web-app.js](https://core.telegram.org/bots/webapps) | Официальный JS для Web Apps |

### Стартовые шаблоны
| Название | Стек | Описание |
|----------|------|----------|
| [vite-twa-template](https://github.com/nicokosi/vite-twa-template) | Vite + React | Минималистичный шаблон |
| [twa-dev/boilerplate](https://github.com/nicokosi/vite-twa-template) | React + TypeScript | Официальный бойлерплейт |

---

## 🔗 TON & Web3

### TON Connect
| Ресурс | Описание |
|--------|----------|
| [TON Connect](https://github.com/ton-connect) | Протокол для подключения кошельков |
| [ton-connect/sdk](https://github.com/ton-connect/sdk) | SDK для интеграции |
| [@tonconnect/ui-react](https://www.npmjs.com/package/@tonconnect/ui-react) | React компоненты |

### TON SDK
| Название | Описание |
|----------|----------|
| [ton](https://github.com/ton-core/ton) | TypeScript SDK для TON |
| [pytoniq](https://github.com/yungwine/pytoniq) | Python библиотека для TON |
| [tonutils-go](https://github.com/xssnick/tonutils-go) | Go библиотека для TON |

### Документация
- 📘 [TON Docs](https://docs.ton.org/) — Официальная документация
- 📘 [TON Dev](https://ton.org/dev) — Портал разработчика

---

## 🚀 Хостинг и деплой

### Рекомендуемые сервисы (работают из РФ)
| Сервис | Описание | Оплата из РФ |
|--------|----------|--------------|
| [Amvera](https://amvera.ru/) | Российский PaaS | ✅ Рубли |
| [Selectel](https://selectel.ru/) | Российский облачный провайдер | ✅ Рубли |
| [TimeWeb Cloud](https://timeweb.cloud/) | VPS и облако | ✅ Рубли |
| [REG.RU](https://reg.ru/) | Домены + VPS | ✅ Рубли |
| [Beget](https://beget.com/) | Хостинг + VPS | ✅ Рубли |

### Международные (нужна крипта/VPN)
| Сервис | Описание |
|--------|----------|
| [Railway](https://railway.app/) | Деплой из GitHub |
| [Render](https://render.com/) | Free tier для ботов |
| [Fly.io](https://fly.io/) | Edge-деплой |
| [Vercel](https://vercel.com/) | Serverless для Mini Apps |

---

## 💳 Приём платежей

### Для Telegram-ботов
| Провайдер | Описание | Комиссия |
|-----------|----------|----------|
| [Telegram Stars](https://core.telegram.org/bots/payments#telegram-stars) | Встроенные платежи Telegram | ~30% |
| [YooKassa](https://yookassa.ru/) | Российский провайдер | от 3.5% |
| [TON Payments](https://docs.ton.org/develop/dapps/ton-connect/transactions) | Криптоплатежи TON | ~0% |
| [CryptoBot](https://t.me/CryptoBot) | Криптоплатежи в TG | 0.5% |
| [Robokassa](https://robokassa.com/) | Агрегатор платежей | от 3% |

### Для физлиц
| Способ | Описание |
|--------|----------|
| СБП / Перевод на карту | Самый простой способ |
| USDT (TRC20) | Криптоплатежи без комиссий |
| @wallet в Telegram | Встроенный кошелёк |

---

## 📖 Туториалы

### Официальные
- 📘 [Telegram Bot API](https://core.telegram.org/bots/api) — Документация API
- 📘 [Bot Features](https://core.telegram.org/bots/features) — Возможности ботов
- 📘 [Mini Apps Docs](https://core.telegram.org/bots/webapps) — Документация TWA

### На русском
- 📺 [aiogram 3.x уроки](https://www.youtube.com/results?search_query=aiogram+3+уроки) — YouTube туториалы
- 📝 [Habr: Telegram боты](https://habr.com/ru/search/?q=telegram+бот) — Статьи на Хабре
- 📝 [Tproger: Боты](https://tproger.ru/?s=telegram+бот) — Туториалы

---

## 📢 Telegram-каналы

### Разработка
| Канал | Описание |
|-------|----------|
| [@tikitech](https://t.me/tikitech) | Mini Apps и TWA разработка |
| [@aiaborot](https://t.me/aiaborot) | Aiogram сообщество |
| [@pythonist](https://t.me/pythonist) | Python разработка |
| [@webdevblogs](https://t.me/webdevblogs) | Веб-разработка |

### Поиск заказов
| Канал | Описание |
|-------|----------|
| [@itfreelance](https://t.me/itfreelance) | IT фриланс |
| [@remotework](https://t.me/remotework) | Удалённая работа |
| [@freelancehunt_jobs](https://t.me/freelancehunt_jobs) | Заказы с FreelanceHunt |

---

## 🎨 Шаблоны и бойлерплейты

### Telegram боты
| Название | Стек | Описание |
|----------|------|----------|
| [telegram-bot-template](https://github.com/donbarbos/telegram-bot-template) | Python, Aiogram, Docker | Production-ready шаблон |
| [AiogramBotTemplate](https://github.com/arturboyun/AiogramBotTemplate) | Python, Aiogram, FastAPI | С интеграцией FastAPI |

### Mini Apps
| Название | Стек | Описание |
|----------|------|----------|
| [telegram-mini-apps](https://github.com/nicokosi/vite-twa-template) | React, Vite | Стартовый шаблон |

---

## 🛠 Инструменты

### Разработка
| Инструмент | Описание |
|------------|----------|
| [BotFather](https://t.me/BotFather) | Создание и настройка ботов |
| [Telegram Test](https://t.me/test) | Тестовый чат |
| [ngrok](https://ngrok.com/) | Туннели для вебхуков |

### Аналитика
| Инструмент | Описание |
|------------|----------|
| [Amplitude](https://amplitude.com/) | Аналитика событий |
| [Posthog](https://posthog.com/) | Open-source аналитика |

---

## 🤝 Contributing

Хотите добавить ресурс? Открывайте PR!

1. Fork этого репозитория
2. Добавьте ваш ресурс в соответствующий раздел
3. Откройте Pull Request

---

## 📄 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

<div align="center">

**Сделано с ❤️ [Egor Terskii](https://github.com/Chumbayoumba)**

[![Telegram](https://img.shields.io/badge/Связаться-@longfest-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/longfest)

</div>