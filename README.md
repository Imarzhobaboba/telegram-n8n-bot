# Telegram Ollama Bot

Простой телеграм-бот, работающий на Ollama с использованием n8n и Docker.

## Технологии
- **Ollama** - локальный запуск LLM моделей
- **n8n** - автоматизация workflows
- **Ngrok** - туннель для Telegram webhook
- **Docker** - контейнеризация
- **Telegram Bot API** - общение с пользователями

## Как запустить

1. Убедитесь, что у вас установлены:
   - Docker
   - Docker Compose
   - Git

2. Клонируйте репозиторий:
```bash
git clone https://github.com/Imarzhobaboba/telegram-n8n-bot.git
cd telegram-n8n-bot
