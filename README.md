# Identifying High-Quality Leads with AI  

## 📌 Project Overview

This project presents an AI-powered lead qualification workflow built for **BrewMasters Coffee Catering**, a company that provides gourmet coffee bars for events.

As bookings increased, manual lead sorting slowed response times. Sales staff were copying form data into spreadsheets, and high-value corporate or repeat clients were sometimes delayed. Meanwhile, low-budget or unclear inquiries overwhelmed the workflow. This automation solves that problem using n8n, AI lead scoring, and conditional routing.

---

## 🚀 Solution Summary

The system captures website form submissions and routes them through an automated workflow:

1. **Webhook Trigger** – Captures form submission data  
2. **Edit Fields Node** – Normalizes and maps inputs  
3. **AI Lead Scoring (LLM)** – Assigns a value score in structured JSON  
4. **Code Node** – Merges AI output with original form data  
5. **Google Sheets Node** – Logs all leads for centralized tracking  
6. **IF Node** – Evaluates lead confidence score  
   - ✅ High-value leads → Instant Gmail alert  
   - 🔎 Low-value or unclear leads → Manual review sheet  

---

## 🧠 Key Concepts Demonstrated

- Webhook automation in n8n  
- Data normalization and field mapping  
- AI classification with structured JSON output  
- JavaScript data parsing in the Code node  
- Conditional logic routing  
- Google OAuth configuration and API integration  

---

## ⚙️ Tools & Technologies

- n8n  
- Google Sheets API  
- Gmail API  
- Large Language Model (LLM)  
- JavaScript  

---

## 📈 Business Impact

- Faster response to premium clients  
- Reduced manual lead sorting  
- Organized and centralized tracking  
- Scalable system for future growth  

---

## 🎓 Lessons Learned

- Plan data schema and field mappings before building  
- Verify OAuth credentials early to avoid access errors  
- Use structured JSON for reliable automation  
- Secure API keys using environment variables  

---

## 📎 Presentation

The full PowerPoint presentation is included in this repository.

---

**Creator:** A. Partida  
AI Automation Specialist
