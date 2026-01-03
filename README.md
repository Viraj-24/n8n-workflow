# WhatsApp PDF Summarizer using n8n 🤖📄

This project is an **automation workflow built with n8n** that allows users to send a **PDF via WhatsApp** and receive a **summarized response automatically** using OpenAI.

The workflow integrates **Twilio WhatsApp API**, **n8n**, and **OpenAI** to create a real-time document understanding assistant.

---

## 🚀 Features

- 📩 Receive messages and PDFs from WhatsApp
- 📄 Detect whether the message contains a PDF
- ⬇️ Download the PDF securely from Twilio
- 📝 Extract text content from the PDF
- 🤖 Summarize the document using OpenAI
- 📤 Send the summary back to WhatsApp automatically
- 🔐 Secure handling of API keys using n8n credentials

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation
- **Twilio WhatsApp API** – WhatsApp messaging
- **OpenAI API** – Text summarization
- **Git & GitHub** – Version control

---

## 🧠 Workflow Logic

1. WhatsApp message is received via Twilio webhook  
2. n8n webhook captures the incoming request  
3. IF condition checks whether media (PDF) is present  
4. PDF is downloaded using Twilio Media URL  
5. Text is extracted from the PDF  
6. Extracted content is sent to OpenAI for summarization  
7. Summary is sent back to the user on WhatsApp  

---
