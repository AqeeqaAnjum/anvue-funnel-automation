# anvue-funnel-automation
Android-based automation system to operate multiple Tinder/Bumble accounts, drive traffic to Snapchat, and convert users into Fanvue subscribers — powered by real devices, proxy rotation, and anti-ban logic.

# Fanvue Funnel Automation System

This repository contains the complete Android automation system designed to run multiple Tinder/Bumble accounts in parallel on **real Android devices**, automatically interact with users, and funnel them through Snapchat to a Fanvue profile.

---

## 💼 Purpose

The system is used to:
- Launch and manage **multiple dating profiles** simultaneously (5+ accounts)
- **Auto-swipe**, **auto-match**, and **auto-message** matched users
- Redirect users to a **Snapchat account**, and from there to **Fanvue**
- Operate discreetly with **proxy rotation**, **device spoofing**, and **ban protection**
- Prepare logs and data for an upcoming control dashboard

---

## 📦 System Modules (Phase 1 – Backend Bot Engine)

| Module | Description |
|--------|-------------|
| `automation/swipe_bot.py` | Automates swiping, match detection, and Snap message drop |
| `automation/profile_creator.py` | Auto-generates Tinder/Bumble profiles |
| `automation/proxy_handler.py` | Assigns and rotates proxy per account |
| `automation/message_sender.py` | Sends templated Snap messages on match |
| `config/bot_settings.json` | Stores timing, delays, and message templates |
| `data/logs/` | Collects logs per account session for match and message tracking |

---

## 🛠️ Tech Stack

- **Python 3.10+** for automation logic
- **ADB / UIAutomator / Appium** to control real Android devices
- **5sim / SMS-Activate** API for phone verification
- **Manual + automated spoofing tools** for fingerprint protection
- **VS Code** for local development
- **Docker (optional)** for backend packaging in later phases

---

## 🧪 Current Status

✅ Project initialized  
🚧 Automation scripts under development  
🖥️ Dashboard to be built after core system is stable

---

## 👤 Team Roles

- **Client**: Product direction, growth goals
- **Mediator**: Project coordination, requirement clarification
- **Developer (You)**: System architect, backend automation lead

---

## 📌 License

**Private/internal use only.** Do not redistribute, resell, or operate outside intended terms without written approval.

---

## 📞 Contact

If you're a project stakeholder or part of the deployment team, please coordinate through the project mediator for technical updates and staging requests.


