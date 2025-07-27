# 📅 Smart Reminder System using n8n

A smart and automated reminder system built using [n8n](https://n8n.io/), integrated with Google Calendar, Google Sheets, Gemini AI, and Telegram Bot to notify users about upcoming tasks in real time.

## 🚀 Project Overview

This project is designed to automate reminders using two different approaches. Notifications are delivered via Telegram Bot, enabling instant alerts based on either calendar events or structured spreadsheet data.

### ✅ Features
- Two flexible automation approaches:
  - **Approach 1:** Google Calendar + Gemini AI + Telegram Bot
  - **Approach 2:** Google Sheets + Telegram Bot
- Sends automated, customized reminders
- Gemini AI integration for natural language understanding
- No-code/low-code solution using n8n

---

## ⚙️ Tech Stack

| Tool | Purpose |
|------|---------|
| `n8n` | Workflow automation |
| `Google Calendar` | Schedule events (Approach 1) |
| `Gemini AI` | Enhance and format messages (Approach 1) |
| `Google Sheets` | Structured data source (Approach 2) |
| `Telegram Bot` | Reminder delivery |

---

## 🧠 Approaches

### 🔹 Approach 1: Google Calendar + Gemini + Telegram
1. User creates an event in Google Calendar with a description and scheduled time.
2. n8n reads the calendar event.
3. Gemini AI processes and formats the description.
4. Telegram Bot sends a smart reminder.

### 🔹 Approach 2: Google Sheets + Telegram
1. User enters tasks in a Google Sheet with columns like `Date`, `Time`, `Event`, and `Note`.
2. n8n checks for tasks matching today’s date.
3. Sends corresponding reminders directly via Telegram Bot.

---

## 🔧 How It Works

1. Create workflows in n8n using triggers and API integrations.
2. Authenticate with Google services (Calendar or Sheets).
3. Connect the Telegram Bot via its API token.
4. Schedule n8n workflow to run periodically (e.g., every day).
5. Get reminder messages in Telegram based on input source.

---

## 📌 Use Cases

- Personal daily task reminders
- Exam/Interview alerts
- Work task notifications
- Group reminders (if extended)

---

## 🔮 Future Enhancements

- Support for SMS or email notifications
- Voice assistant or WhatsApp reminders
- User interface for easier event entry
- Mobile App integration

---

## 👨‍💻 Author

**Kalyan Kumar Reddy**  
B.Tech - AI & ML @ NRI Institute of Technology  
Email: [kalyankumar.muli@gmail.com](mailto:kalyankumar.muli@gmail.com)

---


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
