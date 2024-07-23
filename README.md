# Real-Time Crypto/Stock Tracker

This project is a mini-website that collects and displays real-time price data for stocks or cryptocurrencies. It uses Next.js, Typescript, Redux, and MongoDB.

## Features

- Polls real-time data every few seconds for selected stocks or cryptocurrencies using a free API (e.g., LiveCoinWatch, CoinGecko).
- Stores the data in a MongoDB database.
- Fetches and displays the most recent 20 data entries in a dynamic table.
- Updates the table in real-time with new data.
- Includes a modal/popup to switch between different stocks or cryptocurrencies.

## Technologies

- **Frontend**: Next.js, Typescript, Redux
- **Backend**: Node.js, Express (or Next.js API routes)
- **Database**: MongoDB
- **State Management**: Redux with localStorage
- **Data Fetching**: APIs for real-time data

## Setup

### Prerequisites

- Node.js (v14.x or higher)
- MongoDB (locally or a cloud service like MongoDB Atlas)
- A free API key from a real-time data provider (e.g., CoinGecko)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
