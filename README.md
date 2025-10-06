## 🤖 WhatsApp Chatbot Automation using Make, Twilio & Gemini API

A no-code WhatsApp chatbot built with Make (Integromat), Twilio WhatsApp Sandbox, and Google Gemini API to enable real-time, context-aware conversations directly on WhatsApp.

## 🚀 Features

- AI-powered replies using Gemini API

- Context retention with Make Data Store

- End-to-end automation using Twilio and Make

- Scalable and easily extendable

## 🧩 Workflow

- Webhook Trigger: Captures WhatsApp messages via Twilio Sandbox.

- Context Handling: Fetches previous chats from Data Store and merges using Set Variable.

- AI Response: Sends data to Gemini API via HTTP module and gets chatbot-style reply.

- Update & Send: Stores new messages in Data Store and sends response back through Twilio.

## ⚙️ Tools Used
### Tool	        Purpose
- Make (Integromat)	No-code workflow automation
- Twilio Sandbox	WhatsApp messaging interface
- Gemini API	AI text generation
- Data Store	Store chat history
- HTTP Module	API call to Gemini
- Set Variable	Merge messages
