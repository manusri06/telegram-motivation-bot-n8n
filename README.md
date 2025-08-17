#  Telegram Motivation Bot (n8n)

A Telegram bot that sends **daily motivational quotes** automatically at **7:00 AM**, built using [n8n](https://n8n.io).

---

##  Features
-  Automated scheduling (runs every day at 7 AM IST)
-  Sends a motivational quote to a Telegram chat
-  Quotes fetched from [ZenQuotes API](https://zenquotes.io)
-  Built on **n8n** workflow automation tool

---

##  Tech Stack
- **n8n** (workflow automation)
- **Telegram Bot API**
- **ZenQuotes API**

---

##  Repository Structure
- `My workflow.json` → Exported n8n workflow  
- `README.md` → Project documentation  

---

##  How to Use
1. Clone or download this repository.
   ```bash
   git clone https://github.com/manusri06/telegram-motivation-bot-n8n.git

2. Open your n8n editor (self-hosted or cloud).

3. Import the workflow:

    -- Go to Workflow → Import from File
    -- Select My workflow.json

4. Update these values:

    -- Your Telegram Bot Token

    -- Your Chat ID

5. Activate the workflow ✅
