# [your app name here]
FinRus - Financial Backtesting & Monitoring Platform

CodePath WEB103 Final Project

Designed and developed by: [your names here]
Group 20: TF Kevin Parra
Faith Nchang
Duwayne gray
Leo Shen

🔗 Link to deployed app:
https://github.com/leoyangshen/web103_finalproject/tree/main

## About

### Description and Purpose

FinRus is a comprehensive financial application designed for easy backtesting of trading strategies and real-time portfolio monitoring. Built with React, Node.js, Express, and PostgreSQL.

### Inspiration

Backtesting Engine
Multiple Trading Strategies: Support for SMA (Simple Moving Average), RSI (Relative Strength Index), and more
Historical Data Analysis: Test strategies against historical market data
Performance Metrics: Calculate returns, Sharpe ratio, maximum drawdown, and win rates
Visual Analytics: Interactive equity curves and trade history visualization

Portfolio Monitoring
Real-time Tracking: Monitor your investment portfolio in real-time
Position Management: Track individual positions with entry prices and current values
P&L Calculation: Automatic calculation of unrealized profits and losses
Multiple Portfolios: Create and manage multiple portfolios

Strategy Management
Custom Strategies: Create and save custom trading strategies
Strategy Library: Access pre-built strategy templates
Parameter Customization: Fine-tune strategy parameters for optimal performance

## Tech Stack

Frontend:

React 18
React Router v6
Recharts (Data visualization)
Axios (HTTP client)
Vite (Build tool)

Backend:

Node.js
Express.js
Render
PostgreSQL
pg (PostgreSQL client)

## Features

### [Name of Feature 1]

[short description goes here]
Identifies overbought and oversold conditions.

[gif goes here]

### [Name of Feature 2]

[short description goes here]
Generates buy/sell signals based on the crossover of short-term and long-term moving averages.

[gif goes here]

### [Name of Feature 3]

[short description goes here]

[gif goes here]

### [ADDITIONAL FEATURES GO HERE - ADD ALL FEATURES HERE IN THE FORMAT ABOVE; you will check these off and add gifs as you complete them]

## Installation Instructions

[instructions go here]
1. Clone the repository
git clone https://github.com/waynebin/web103_Capstone_FinRus.git
cd web103_Capstone_FinRus

2. Set up the database
Create a PostgreSQL database:
createdb finrus
Run the database schema:
psql -d finrus -f server/config/schema.sql

3. Set up the backend
cd server
npm install
cp .env.example .env
Edit .env with your database credentials:
PORT=3001
DATABASE_URL=postgresql://localhost:5432/finrus
NODE_ENV=development

4. Set up the frontend
cd ../client
npm install

