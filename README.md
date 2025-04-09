# SLOT SNIPER
Slot Sniper is a student-built, AI-powered sniper system for SEB slot booking. It auto-scans, auto-snipes, and force-books CIA, Module, and Viva slots — no refreshing, no waiting.You don’t miss here. You dominate.

# 🎯 SlotSniper

### 🔫 Precision Slot Booking for SEB – Built by a Student, for Students  
**Made by a student. For every student who’s tired of missing their shot.**  
**One shot. One slot. Built for domination.**  
**Automated. Accurate. Always on Target.**

## 📘 Project Overview

**Slot Sniper** is a high-precision, student-built automation system developed by **Gokul M** and powered by **ChatGPT AI**, designed to eliminate the slot-booking struggle faced on the SEB platform at **Saveetha Engineering College**.

It doesn’t guess. It doesn’t hope. It executes.

🧠 Built by Gokul M (a fellow engineering student who got tired of missing out)  
🤖 Powered by ChatGPT AI to create a reliable, always-on sniping system

No more hitting refresh. No more rage. No more “better luck next time.”

Just one shot one slot.

The platform releases all weekly slots — **CIA**, **Module**, and **Viva** — in a bulk drop. These get filled in seconds. SlotSniper operates at the protocol level: monitoring DOM elements, scanning for any sudden changes, and executing bookings before a human can react.

**SlotSniper** neutralizes the mess by:
- Securely authenticating user credentials
- Constant background scanning (every second)
- Watching for canceled or newly released slots
- Force-sniping and auto-booking instantly

Built with a focus on real-world use cases, SlotSniper is more than a script — it's an always-on assistant for students who **refuse to miss a slot again**.

> 🎯 Book like a sniper. Miss nothing. Built by Gokul M and his friend ChatGPT AI.



## 🚀 Features

- 🔐 **Secure Login** – Uses your SEB LMS credentials safely
- 🔄 **Real-Time Scanning** – Checks for available/canceled slots every second
- 🎯 **Sniping Logic** – Rapid DOM scanning, instant slot selection, auto-rebook
- 🧠 **Smart Retry System** – Re-attempts intelligently during peak hours
- 🌐 **Web Interface** – Easy one-page UI, minimal steps for users
- 📊 **User Database** – Tracks user history, avoids double-booking
- 📩 **WhatsApp Confirmation** – Instantly notifies successful booking

---

## 🧰 Tech Stack

| Component        | Tech Used                         |
|------------------|-----------------------------------|
| Frontend         | Flask, HTML/CSS/JS                |
| Backend Server   | Flask / FastAPI                   |
| Real-time Scanner| Python, Selenium                  |
| Scheduling       | APScheduler / Custom Loop         |
| Database         | SQLite / PostgreSQL               |
| Shared State     | Redis / Firebase Realtime DB      |
| Credential Safety| Python Cryptography (Fernet)      |
| Notifications    | Twilio WhatsApp API, SMTP         |
| Deployment       | Railway, Render, EC2, Replit      |

---

## 📁 Folder Structure

```
SlotSniper/
├── app.py                 # Flask app entry point
├── templates/             # HTML templates
│   └── index.html         # Main user interface
├── static/                # CSS and JS assets
├── booking_bot.py         # Main automation logic
├── scheduler.py           # Auto re-booking trigger system
├── config.yaml            # User config & preferences
├── database.py            # User data & slot history
├── notifier.py            # WhatsApp/Email notifications
├── encryptor.py           # Secure credential storage
├── server.py              # Background slot coordination API
├── README.md              # This file
└── requirements.txt       # Python dependencies
```

---

## 🛠️ Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/your-username/SlotSniper.git
cd SlotSniper

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install required packages
pip install -r requirements.txt

# 4. Start the Flask Web Interface
python app.py
```

---

## 🧪 How it Works

```text
[✓] Interface launches → User logs in with SEB credentials
[✓] Scanner activated → Keeps running every second
[✓] Slot appears/cancelled → Auto-snipes and books
[✓] WhatsApp alert sent instantly on success
```

---

## 🔸 Background Architecture (High-Level Overview)

- 💽 **Frontend:** Flask + Bootstrap
- ⚙️ **Automation Core:** Selenium bot
- 📡 **Scanner:** Runs every second
- 📦 **Server:** Flask API + Redis (slot state map)
- 📬 **Notification:** WhatsApp via Twilio
- 🛡️ **Security:** Encrypted credentials (Fernet)


## 🔒 Security & Ethics

> ⚠️ Use responsibly. For educational and ethical purposes only.  
> SlotSniper does NOT hack or exploit — it mimics real user actions efficiently.

- No brute-force, just fast DOM interaction
- Does not bypass login or violate rules
- Data stored securely; not shared


## 👨‍💻 Developers

- **Gokul M** – Student, Project Lead
- **ChatGPT AI** – Co-developer, System Designer


## 📢 Future Roadmap

- [ ] Multi-student dashboard
- [ ] Captcha bypass fallback
- [ ] Admin panel for slot coordination
- [ ] Mobile interface for emergency booking
- [ ] AI-based booking prediction
- [ ] Integration with **CAMU Student App** for centralized booking across systems

## 🧠 Real-World Triggers Captured

- 🔀 Someone cancels → slot freed → **BOOM! Booked**
- 🤚 New slot appears → **BOOM! Sniped**
- ⚠️ SEB reset glitch → new slot opens → **BOOM! Grabbed**
 
**You don’t miss here. You dominate.**
