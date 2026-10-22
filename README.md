# ShopManager 🖥️ — Desktop App for Computer Service Shops

Offline Windows desktop app built for a **real computer-services shop** in Arak, Iran — and used there daily. Intake, invoicing, daily accounting and customer debts, with zero internet needed.

![Platform](https://img.shields.io/badge/platform-Windows-blue) ![Electron](https://img.shields.io/badge/Electron-33-47848F) ![License](https://img.shields.io/badge/license-MIT-green)

## Features
- **Job intake** — customer, device, problem, promised date; printable intake receipt
- **Invoicing** — built-in price catalog (23 services: Windows install, repairs, PC assembly, console game install...)
- **Daily accounting** — cash/card totals, day-close report
- **Customers & debts** — who owes what, since when
- **Reports + Settings** — JSON backup export/import, fully local data (localStorage)

## Install & Run
```bash
npm install
npm start        # run in Electron
npm run dist     # build Windows NSIS installer (ShopManager-Setup-1.0.0.exe)
```
> Unsigned build → Windows SmartScreen may warn: **More info → Run anyway**. No admin needed.

## Why this exists
Most shop software is either bloated accounting suites or nothing. This is the exact middle a small service shop needs — built from the counter of «خدمات کامپیوتری سینا» (Sina Computer Services).

## فارسی 🇮🇷
اپ دسکتاپ آفلاین مدیریت مغازه خدمات کامپیوتر: پذیرش دستگاه، فاکتور با لیست قیمت آماده، حسابداری روزانه و بستن صندوق، مدیریت بدهی مشتری‌ها و گزارش. داده‌ها کاملا روی کامپیوتر خودت می‌مونه. برای سفارش نسخه اختصاصی صنف شما: تلگرام [@sarzamin_game11](https://t.me/sarzamin_game11)

## License
MIT
