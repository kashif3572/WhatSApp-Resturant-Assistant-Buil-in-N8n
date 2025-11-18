# Sanitized n8n WhatsApp Restaurant Assistant Workflow

This repository contains a **fully sanitized** n8n workflow for a WhatsApp-based restaurant assistant.

## 🚀 What has been removed for safety
- API Keys  
- OAuth credentials  
- Google Sheets document IDs  
- WhatsApp phone number IDs  
- Webhook verification tokens  

All sensitive fields are replaced with:
```
ADD_YOUR_CREDENTIALS_HERE
REPLACE_VALUE
REPLACE_SHEET_ID
```

## 📌 How to use
1. Import `sanitized_workflow.json` into your n8n instance.  
2. Open each credential-based node:
   - WhatsApp Trigger  
   - WhatsApp Send  
   - Google Sheets  
   - OpenAI Chat Model  
3. Add your real credentials manually.  
4. Add your real Google Sheet IDs.  
5. Activate the workflow.

## ⚠️ Important
This workflow **will not run** until you add back your own credentials.  
It is safe to upload publicly on GitHub.

