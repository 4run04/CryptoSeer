# 🪙 Crypto Price Tracking App

A real-time cryptocurrency price tracking web app built with **Django**, **Django Channels**, and **Celery**. It fetches live data from external APIs and updates the UI using WebSockets to deliver up-to-date price information seamlessly.

---

## 🚀 Features

- 🔁 Real-time crypto price updates via WebSockets
- 🔄 Background tasks handled with Celery
- 🌐 Live data fetched from external crypto APIs
- 📊 Dynamic frontend updates without page refresh
- 🐘 Redis used as a message broker

---

## 🛠️ Tech Stack

- **Backend:** Django, Django Channels, Celery
- **Frontend:** HTML, CSS, JavaScript (with WebSocket integration)
- **Broker:** Redis
- **Task Queue:** Celery
- **API Source:** [CoinGecko](https://www.coingecko.com/) or other public crypto APIs

---

## 📦 Installation

 **Clone the repository**
  ```bash
   git clone https://github.com/your-username/crypto-price-tracking-app.git
   cd crypto-price-tracking-app

