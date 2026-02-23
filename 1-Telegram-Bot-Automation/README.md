# 🤖 Telegram Bot Integration with n8n Automation

## 📌 Project Overview
This workflow integrates a Telegram Bot with n8n to process incoming webhook data, apply conditional logic, and send automated responses via the Telegram Bot API.

The workflow dynamically routes messages based on different conditions and executes specific actions accordingly.

---

## 🔄 Workflow Logic

1. Webhook receives incoming data
2. Data is cleaned and structured using Edit Fields
3. Conditional logic (Multiple IF nodes) evaluates message type or condition
4. Custom logic is applied using Code nodes
5. Telegram Bot API is triggered using HTTP Request nodes
6. Automated message is sent to users via Telegram

---

## ⚙️ Tools & Technologies Used
- n8n
- Webhook Trigger
- Edit Fields Node
- IF Node (Conditional Logic)
- Code Node (Custom JavaScript)
- HTTP Request Node
- Telegram Bot API

---

## 🚀 Key Features
- Telegram Bot API integration
- Multi-branch conditional logic
- Automated response handling
- Dynamic routing of user messages
- Custom message formatting via Code node
- Scalable bot automation structure

---

## 📷 Workflow Screenshot
![Workflow Screenshot](screenshot.png)

---

## 🧠 Learning Outcome
This project helped me strengthen my understanding of:
- API-based bot integrations
- Multi-level conditional automation
- Message routing systems
- Real-time webhook handling
- Automation architecture design

---

## 💡 Use Case Example
This automation can be used for:
- Customer support bots
- Notification systems
- Command-based Telegram bots
- Automated information delivery systems

