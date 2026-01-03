# CryptoRiskMonitor

CryptoRiskMonitor is a Django-based web application that helps users analyze the risk profile of their crypto portfolios.

## Features
- User authentication (signup / login)
- Portfolio creation with manual or preset crypto assets
- Allocation-based risk analysis
- AI-generated portfolio interpretation
- Security score visualization
- ETH & BTC dominance insights

## Tech Stack
- Backend: Django
- Frontend: Django Templates (HTML/CSS)
- AI: OpenAI API
- Market Data: CoinGecko (via local proxy)
- Database: SQLite (development)

## Environment Variables
Create a `.env` file with the following variables:

```env
SECRET_KEY=your_django_secret_key
DEBUG=True
OPENAI_API_KEY=your_openai_api_key
