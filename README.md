FeeAI Platform

FeeAI is a full-stack trading and liquidity-providing platform built on the Solana blockchain. The platform integrates trading functionality with Jup.AG API, market visualization with TradingView, and liquidity management with Meteora API, making it a one-stop solution for Solana-based decentralized finance (DeFi) users.

Features

Trading Page

Swap Functionality: Seamlessly execute token swaps using Jup.AG's API.

Chart View: Visualize market trends using TradingView.

Positions Overview: Track your holdings and easily create liquidity pools.

Liquidity Pool Creation

Simplified process for creating liquidity pools through Meteora's API.

Fee structure includes 0.25% on buys/sells and standard pool fees + 1% for pool creation.

Project Structure

FeeAI/
|— backend/       # Backend services (API integrations, Solana interactions)
|— frontend/      # Frontend application (React/Next.js)
|— contracts/     # Solana programs for liquidity management
|— scripts/       # Deployment and utility scripts
|— README.md     # Project overview

Technology Stack

Frontend

Framework: React or Next.js

Charting: TradingView API

Backend

Node.js: API integration and transaction handling

Express.js: Backend framework for REST APIs

Blockchain

Solana: For executing smart contracts and managing SPL tokens

Meteora API: For liquidity pool creation and management

APIs Used

Jup.AG API:

URL: https://station.jup.ag/api-v6/post-swap-instructions

Functionality: Token swaps

TradingView API:

Functionality: Market chart visualization

Meteora API:

URL: https://dlmm-api.meteora.ag/swagger-ui/

Functionality: Liquidity pool creation and management

Getting Started

Prerequisites

Node.js: Install from https://nodejs.org/

Solana CLI: Install from https://docs.solana.com/cli

Docker: Optional, for containerized deployment

Installation

Clone the repository:

git clone https://github.com/yourusername/FeeAI.git
cd FeeAI

Install dependencies:

Backend:

cd backend
npm install

Frontend:

cd frontend
npm install

Configure environment variables:

Create .env files in both backend and frontend directories.

Add API keys for Jup.AG, TradingView, and Meteora.

Running the Platform

Frontend

cd frontend
npm run dev

Backend

cd backend
npm start

Deployment

Use Docker for containerized deployment or deploy the frontend to services like Vercel/Netlify and backend to AWS/GCP.

Contribution Guidelines

We welcome contributions to FeeAI! To contribute:

Fork this repository.

Create a new branch for your feature or bug fix.

Commit your changes and push them to your fork.

Open a pull request to this repository.

Please ensure your code adheres to our coding standards and is well-documented.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact

For any questions or support, please contact us at feeai@mail.com

