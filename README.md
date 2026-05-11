# 📬 Form Notifier — уведомления с сайта в Telegram и Google Sheets

## Что делает
Получает данные с формы сайта (имя, телефон, сообщение) и одновременно отправляет их в Telegram-бот и записывает в Google Sheets.

## Схема работы
Webhook → Telegram Bot → Google Sheets

## Реализации

### ✅ n8n (self-hosted)
- Инструмент: n8n на собственном сервере (n8n.ezi.ru)
- Файл воркфлоу: [n8n/massash-form.json](n8n/massash-form.json)
- Стек: n8n, Telegram Bot API, Google Sheets API

### ✅ Make.com
- Инструмент: Make.com (облачная автоматизация)
- Стек: Make.com, Telegram Bot API, Google Sheets

## Живой пример
Используется на [massash.com](https://massash.com)

## Зачем
Мгновенные уведомления о новых заявках с сайта. Все заявки автоматически сохраняются в таблицу — история не теряется.

<img width="1760" height="539" alt="image" src="https://github.com/user-attachments/assets/5a1e57b5-24cc-4eb1-99e4-180c5922a149" />
<img width="1675" height="772" alt="image" src="https://github.com/user-attachments/assets/8496e52a-96dd-498e-98fb-214b81aa2af0" />

