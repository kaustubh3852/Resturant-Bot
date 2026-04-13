# 🍽️ Restaurant Chatbot

An AI-powered restaurant chatbot built using n8n workflow 
automation, integrated with Google Gemini AI and Telegram.

## 🚀 Features

- 🤖 AI-powered conversations using Google Gemini
- 📋 Real-time menu from Google Sheets
- 📦 Automated order management
- ❓ FAQ support
- 🧠 Conversation memory
- 🌐 Multilingual support (Hindi/English)
- 📱 Deployed on Telegram

## 🛠️ Tech Stack

- **n8n** - Workflow automation
- **Google Gemini AI** - Language model
- **Google Sheets** - Database for menu, orders, FAQ
- **Telegram Bot API** - Customer interface
- **Prompt Engineering** - Custom AI behavior

## 📊 How It Works

1. Customer sends message on Telegram
2. n8n receives message via Telegram Trigger
3. AI Agent processes message using Gemini
4. Checks inventory/FAQ from Google Sheets
5. Confirms order and saves to Orders sheet
6. Sends reply back to customer on Telegram

## 📁 Project Structure

- `workflow.json` - n8n workflow file
- `screenshots/` - Project screenshots

## 🔧 Setup

1. Import `workflow.json` in n8n
2. Add Google Gemini API key
3. Connect Google Sheets OAuth
4. Add Telegram Bot token
5. Activate workflow

## 📸 Demo

<img width="1919" height="953" alt="Screenshot 2026-04-13 154040" src="https://github.com/user-attachments/assets/5f4183ca-d4a8-447d-84b9-2630372c0802" />
![WhatsApp Image 2026-04-13 at 5 02 05 PM](https://github.com/user-attachments/assets/a9672d32-6607-4cfa-aa0a-1c0f9d347c59)
![WhatsApp Image 2026-04-13 at 5 02 06 PM](https://github.com/user-attachments/assets/a37339a3-612b-431b-a010-4ce78fe7d2b9)
![WhatsApp Image 2026-04-13 at 5 02 07 PM](https://github.com/user-attachments/assets/b72538b0-eee8-43aa-a769-31d986de05d4)
![WhatsApp Image 2026-04-13 at 5 02 07 PM](https://github.com/user-attachments/assets/91b1bcc3-51a9-4547-a55e-d9155cf42c23)



## 👨‍💻 Author

Kaustubh Raj
