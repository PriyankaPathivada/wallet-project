# Wallet Service

## APIs

### POST /api/v1/wallet
{
  "walletId": "uuid",
  "operationType": "DEPOSIT",
  "amount": 100
}

### GET /api/v1/wallets/{id}

## Run

docker-compose up --build

## Features
- Liquibase migrations
- Optimistic locking
- Dockerized
