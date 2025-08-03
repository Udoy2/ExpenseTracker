# 💸 Telegram Expense Tracker Bot
![Expense Tracker Demo](/assets/n8n_demo.png)


A smart expense tracking bot built with **n8n** and integrated with **Telegram**. It allows users to log expenses, delete entries, and get weekly/monthly reports — all via simple chat commands. 💬📊

---

## 🚀 Features

- ➕ Add an expense: `Item Price` (e.g., `Milk 50`)
- 🗑️ Delete the last added entry: `/erase`
- 📊 Get a 30-day weekly expense report: `/report`
- 🧾 Show help menu: `/help`
- ⚠️ Delete entire database: `/deleteAll`

---

## 🔧 Tech Stack

- 🧠 [n8n](https://n8n.io/) – Visual workflow automation
- 📡 Telegram Bot API
- ☁️ Firebase Realtime Database (or any backend via REST API)

---

## 🛠️ Setup Instructions

1. **Clone this repository** or import the JSON workflow into your [n8n instance](https://docs.n8n.io/hosting/overview/).
2. **Configure Credentials**:
   - Set up your Telegram Bot Token.
   - Connect your Firebase (or custom backend) credentials.
3. **Customize URLs** in the HTTP Request nodes (e.g., `https://url/items.json`) to match your backend endpoint.
4. **Replace `your_id`** in Telegram nodes with your actual Telegram Chat ID.
5. Activate the workflow in n8n.

---
## 🖼️ Example
✅ Will be saved as:

- Item: Milk  
- Price: 50  
- Date: Today (auto-extracted from Telegram)

---

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Support & Contributions

Feel free to open issues, submit pull requests, or suggest improvements! 🤝  
Happy budgeting! 💰



