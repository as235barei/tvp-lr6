# TechShop — Лабораторна робота №6

Тема роботи — функціонал для користувачів сайту TechShop: перегляд каталогу,
кошик, оформлення замовлень та відгуки. Стек той самий, що й у попередніх роботах:
React-клієнт, REST API на Express і база даних MySQL.

## Технології

- React + Vite (`client/`)
- Node.js + Express (`server/`)
- MySQL (`database/`)
- JWT

## Як запустити

1. База даних у Docker:

```bash
docker compose -p techshop up -d db
```

2. Сервер:

```bash
cd server
cp .env.example .env
npm install
npm run dev
```

3. Клієнт:

```bash
cd client
npm install
npm run dev
```

## Тестові акаунти

- Адміністратор: `admin@techshop.local` / `admin1234`
- Користувач: `user@techshop.local` / `user1234`
