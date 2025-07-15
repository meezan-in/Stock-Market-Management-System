# Real-Time Stock Trading Platform

A comprehensive full-stack trading platform for real-time stock portfolio management and analytics. This platform delivers live stock data updates for over 100 companies, empowering users to track investments, analyze performance, and access actionable insights with ease.

## Features

- **Real-Time Portfolio Tracking:** Instantly monitor your portfolio with live updates and performance metrics.
- **Live Stock Data:** Access up-to-date stock prices and financial news, automatically aggregated from multiple sources.
- **Automated Data Pipelines:** Utilizes Puppeteer to scrape Google Finance and financial news, reducing manual data collection by 95%.
- **Natural Language Analytics:** Integrated Groq LLM-powered chatbot enables users to perform natural language SQL queries for portfolio analytics, making advanced insights accessible to everyone.
- **Modern, Responsive UI:** Built with React.js for a seamless and intuitive user experience.
- **Robust Backend:** Node.js server with PostgreSQL database for reliable, scalable data management.

## Technology Stack

- **Frontend:** React.js
- **Backend:** Node.js
- **Database:** PostgreSQL
- **Web Scraping:** Puppeteer
- **AI/Analytics:** Groq LLM-powered chatbot for natural language SQL

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- PostgreSQL database

### Installation

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd <project-directory>
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Configure Environment:**
   - Set up your PostgreSQL database and update the connection string in the environment variables or configuration file.
   - (Optional) Configure API keys or credentials for financial data sources if required.
4. **Run the application:**
   ```bash
   npm start
   ```
5. **Access the platform:**
   Open your browser and navigate to [http://localhost:3000](http://localhost:3000)

## Usage

- **Add and manage your stock portfolio.**
- **View real-time updates and analytics.**
- **Ask natural language questions about your portfolio and receive instant insights.**

## License

MIT

---

_For questions or contributions, please open an issue or pull request!_
