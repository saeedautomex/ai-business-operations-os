# 🤖 AI Business Operations OS

An AI-powered business automation system built with n8n and OpenAI.

This system intelligently understands incoming business requests, classifies them, detects priority, and routes them to the correct department automatically.

---

## 🚀 How It Works

Incoming Request  
↓  
Webhook  
↓  
Normalize Request  
↓  
Master AI Router  
↓  
AI Decision Parser  
↓  
Department Router  
↓  
Sales / Support / Operations / Documents / Human Review  
↓  
Final Response

---

## 🧠 AI Capabilities

The Master AI Router analyzes incoming requests and classifies them into:

- 💰 Sales
- 🛠️ Customer Support
- ⚙️ Operations
- 📄 Document Intelligence
- 👤 General / Human Review

The AI also detects:

- Request intent
- Priority level
- Human escalation requirement
- Recommended next action
- AI-generated response

---

## 🔄 Workflow Architecture

Webhook  
↓  
Normalize Request  
↓  
Master AI Router  
↓  
Parse AI Decision  
↓  
AI Department Router  
├── Sales Automation  
├── Support Automation  
├── Operations Automation  
├── Document Automation  
└── General / Human Review  
↓  
Final JSON Response

---

## 🛠️ Tech Stack

- n8n
- OpenAI
- Webhooks
- AI Routing
- Workflow Automation
- JSON Data Processing

---

## 📌 Example Request

I want to know your pricing and book a demo.

### AI Classification

```json
{
  "category": "SALES",
  "priority": "MEDIUM",
  "needs_human": false
}
