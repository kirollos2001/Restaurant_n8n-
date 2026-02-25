# Restaurant n8n Automated Customer Support

![n8n](https://img.shields.io/badge/n8n-%23FF6611.svg?style=for-the-badge&logo=n8n&logoColor=white) ![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-%238E75B2.svg?style=for-the-badge&logo=google-gemini&logoColor=white) ![AI RAG](https://img.shields.io/badge/AI%20RAG-000000?style=for-the-badge&logo=openai&logoColor=white)

![Architecture](architecture.png)

This project is an automated customer service system for a restaurant, built using [n8n](https://n8n.io/).
The workflow enables customers to interact with the restaurant through Telegram, allowing them to:
- View the menu
- Place orders
- Track their orders
- Cancel orders

The system leverages AI + RAG (Retrieval-Augmented Generation) for intelligent responses and dynamic menu retrieval.

## 🚀 Features

### ✅ Telegram Integration
Customers communicate directly with the bot via Telegram. It provides a seamless interface for ordering and inquiries.

### ✅ Menu Display via RAG
The menu is retrieved dynamically using a RAG-based knowledge system. Ensure customers get up-to-date options tailored to their needs.

### ✅ AI Agent
Handles customer conversations and decision-making, providing human-like interaction and accurate query resolution.

### ✅ Order Management
- **Create new orders:** Seamlessly walk users through choosing items and placing their requests.
- **Track existing orders:** Check the status of current orders in real time.
- **Cancel orders:** Allow customers to cancel their orders if needed.

### ✅ Google Sheets Integration
Acts as the database for the operation:
- Store order data
- Read order information
- Update order status

## 📁 Repository Structure
- `restaurant_Customer_support.json`: The exported n8n workflow file containing the complete logic for the AI-powered support system.

## 🛠 Setup Instructions
1. Import the `restaurant_Customer_support.json` file into your n8n instance.
2. Configure your Telegram Bot API credentials.
3. Connect your Google Sheets account and point to your orders spreadsheet.
4. Setup your RAG vector store and AI Agent models inside n8n.
5. Activate the workflow and test the Telegram bot.
