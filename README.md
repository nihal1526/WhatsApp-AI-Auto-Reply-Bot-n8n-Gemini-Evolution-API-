# 🤖 WhatsApp AI Auto-Reply Bot

This project is an automated WhatsApp chatbot built using n8n, Google Gemini AI, and Evolution API. It receives incoming WhatsApp messages via webhook, processes them using AI, and sends intelligent replies automatically.

---

## 🚀 Features

- WhatsApp webhook integration
- AI-powered auto-replies using Google Gemini
- Business-focused conversation handling
- Lead generation and customer engagement
- Memory-based conversation context
- Custom knowledge base support
- Dynamic API-based message sending
- Real-time response automation

---

## 🧠 How It Works

1. User sends a message on WhatsApp  
2. Webhook receives incoming message  
3. Data is formatted and cleaned  
4. AI Agent processes the message  
5. Generates a contextual response  
6. Response is sent via Evolution API  
7. User receives instant reply  

---

## 🔄 Workflow Diagram

```mermaid
flowchart LR
    A[WhatsApp User] --> B[Webhook]
    B --> C[Process Data]
    C --> D[AI Agent - Gemini]
    D --> E[Generate Response]
    E --> F[Send via API]
    F --> G[WhatsApp Reply]
