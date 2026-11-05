# Sami – AI Customer Service Agent for Aramex Tunisia 🤖📦

> Built during my AI Software Engineer internship at **Aramex Tunisia** (June – July 2026).
> The production source code is confidential and not published here; this repository hosts the project presentation page.

**Sami** is an AI customer service agent live on **Facebook Messenger** and **WhatsApp**. It is connected directly to the Aramex API, so it does not just answer questions: it understands the request, decides what to do and executes the operation.

🎥 Demo video: see my [LinkedIn post](https://www.linkedin.com/in/omar-abdallah1/recent-activity/all/).

## ✨ Features — 9 business modules
| Module | What Sami does |
|---|---|
| 📦 Shipment tracking | Tracks a parcel in real time |
| 📋 Complaints | Files a complaint automatically |
| 📅 Rescheduling | Changes the delivery date |
| 🌍 Rate quotes | Validates country, city and postal code, then gives the international rate |
| 🚚 New shipment | Creates the shipment, generates the waybill and sends a confirmation email |
| 🏠 Pickups | Creates or securely cancels a pickup request |
| 📍 Office lookup | Finds the nearest Aramex office |
| ⏰ Proactive alerts | A cron job checks delayed shipments every 5 minutes and notifies customers before they complain |
| 🚨 Human escalation | Hands the conversation to an agent when needed |

## 🧠 Intelligence
- Understands **4 languages**: Tunisian Darija, Arabic, French and English, without asking the customer to switch.
- **Sentiment detection**: adapts its tone for frustrated or anxious customers.
- **Local LLM** (Ollama + Qwen3): customer conversations are never sent to a third-party AI API.

## ⚙️ Architecture & stack
| Layer | Technology |
|---|---|
| Backend | Node.js, Express |
| Messaging | Meta Cloud API (Messenger + WhatsApp) |
| LLM | Ollama + Qwen3 (self-hosted) |
| Sessions | Redis |
| Database | PostgreSQL + Prisma |
| Admin | JWT-secured dashboard |
| Jobs | Cron-based proactive alert system |

## 🚀 Results
- ✅ 100% of messages handled
- ⚡ Under 1 second response time
- 🕐 24/7 availability
- 🌍 4 languages understood

---
👤 **Omar Abdallah** · [LinkedIn](https://www.linkedin.com/in/omar-abdallah1) · [GitHub](https://github.com/OmarAbdallah25)
