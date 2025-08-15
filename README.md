# Email Summary

## 🤖 n8n Gmail to Telegram Notifier

An intelligent email filtering system that automatically analyzes incoming Gmail messages and sends notifications about important emails directly to Telegram.

---

## 📋 Description

This project automates the process of monitoring your inbox and applying personalized message filtering. The system evaluates incoming emails based on predefined importance criteria and instantly notifies you via Telegram about critical messages — so you never miss what matters.

---

## 🎯 Features

- ✅ **Automatic Email Checks**: Regularly scans your Gmail inbox for new messages  
- ✅ **Smart Importance Scoring**: Rates emails on a scale from 1 (low) to 5 (critical)  
- ✅ **Instant Telegram Alerts**: Real-time notifications for high-priority emails (level 4–5)  
- ✅ **Rich Message Formatting**: Clean, readable notifications with sender, subject, and preview  
- ✅ **24/7 Automation**: Runs continuously without manual intervention  

---

## 🛠 Technologies Used

- 🔄 **[n8n](https://n8n.io)** – Open-source workflow automation platform  
- 📧 **Gmail API** – Secure access to your email inbox  
- 📱 **Telegram Bot API** – Reliable and instant messaging integration  
- ☁️ **Cloud Hosting** – Ensures 24/7 availability (e.g., on Docker, Kubernetes, or VPS)  

---

## 🚀 Getting Started

1. 📥 Copy the workflow from this project into your n8n instance  
2. 🔧 Configure connections to **Gmail** and **Telegram** (create a bot via @BotFather)  
3. ⏱ Set the desired polling interval (e.g., every 5–10 minutes)  
4. ▶️ Activate the workflow and let it run  
5. 💬 Start receiving smart email alerts in your Telegram!

---

## 📊 How It Works

1. **Polling**: Checks for new emails at regular intervals  
2. **Analysis**: Evaluates sender, subject, keywords, and content  
3. **Scoring**: Assigns an importance level (1–5) using custom logic or AI rules  
4. **Filtering**: Only high-priority emails (level 4–5) trigger notifications  
5. **Alerting**: Sends a formatted message to your Telegram chat  

---
