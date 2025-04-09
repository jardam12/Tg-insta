# Instagram Ads Bot

Telegram-бот для запуска рекламы в Instagram через Meta Ads API.

## Возможности

- Принимает ссылку, бюджет, пол, возраст и страну
- Создает рекламную кампанию, группу и объявление
- Работает на Python + aiogram + Meta Ads API

---

## Установка локально

```bash
git clone https://github.com/your-user/insta-ads-bot.git
cd insta-ads-bot
pip install -r requirements.txt
python bot.py
```

---

## Развёртывание на [Render](https://render.com)

1. Залей репозиторий на GitHub
2. Перейди на [https://render.com](https://render.com)
3. Создай **New Web Service**
4. Подключи репозиторий с ботом
5. Укажи:
   - **Start Command**: `python bot.py`
   - **Environment Variables**:

```
API_TOKEN=твой_токен_бота
META_ACCESS_TOKEN=access_token_из_Meta
AD_ACCOUNT_ID=act_...
PAGE_ID=...
```

6. Нажми **Deploy**

---

## Стек

- Python
- aiogram
- requests
- Meta Ads Graph API

---

## Контакт

Разработчик: @твой_телеграм
