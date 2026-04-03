# IntelliReach WhatsApp AI Sales Agent

**Intelligent WhatsApp Bot** built with **n8n** that acts as an official sales agent for IntelliReach.

Automatically introduces the company, lists services, gathers client requirements, checks calendar availability, and books Zoom meetings.

---

## ✨ Features

- Fully automated WhatsApp conversation flow
- Company introduction + service catalog
- Requirement gathering for Web Development & other services
- Real-time Google Calendar availability check
- Automatic Zoom meeting creation + Google Calendar event
- Persistent memory (remembers previous conversations per user)
- Powered by Groq (Llama 3.3 70B)

## 🛠 Tech Stack

- n8n (Workflow Automation)
- Groq LLM (llama-3.3-70b-versatile)
- WhatsApp Business Cloud API
- Google Calendar + Zoom

## 🚀 How to Use

1. Import the JSON file into your n8n instance
2. Set up the following credentials:
   - WhatsApp Account
   - WhatsApp Trigger (OAuth)
   - Groq API
   - Google Calendar (OAuth2)
   - Zoom (OAuth2)
3. Update the `phoneNumberId` if needed
4. Activate the workflow

## 📁 Files

- `intellireach-whatsapp-ai-agent.json` → Main n8n workflow

## 📝 Setup Notes

Replace all placeholder credentials with your own before activating the workflow.

---

Made with ❤️ for **IntelliReach** by Tarun Goel
