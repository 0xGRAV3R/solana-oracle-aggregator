# Oracle Aggregator for DeFi Application

This project is a decentralized finance (DeFi) application designed to enhance the accuracy and reliability of SOL/USD price information. It achieves this by aggregating price feeds from multiple oracle sources, ensuring that the data is comprehensive and up-to-date. The application then calculates an average price from these diverse inputs to provide a balanced and accurate representation of the SOL/USD market value. This calculated average price is subsequently displayed on the frontend, offering users a clear and reliable view of the current market trends and valuations. Through this process, the application aims to deliver a robust and transparent price discovery mechanism for the DeFi community.

## Project Overview

The Oracle Aggregator retrieves price data from two distinct oracle sources:

-Pyth Network
-Dia API

After gathering the data, it computes the average SOL/USD price and presents it on the frontend using React and TypeScript.

## Requirements

To run this project locally, ensure you have Node.js installed on your machine.

## Getting Started

### 1. Clone the repository:

```bash
git clone https://github.com/0xGRAV3R/solana-oracle-aggregator.git
```

### 2. Navigate into the project directory:

```bash
cd solana-oracle-aggregator
```

### 3. Install dependencies using npm:

```bash
npm install
```

### 4. Run the application:

```bash
npm start
```

### 5. Open your browser and navigate to http://localhost:3000 to view the application.
