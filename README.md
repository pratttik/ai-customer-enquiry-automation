# AI Customer Enquiry Automation using n8n, Google Gemini & Twilio WhatsApp

<p align="center">

![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-orange?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Google-Gemini-blue?style=for-the-badge)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-Database-green?style=for-the-badge)
![Twilio](https://img.shields.io/badge/Twilio-WhatsApp-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)

</p>

---

## Overview

This project is an AI-powered customer enquiry automation system built using **n8n**, **Google Gemini AI**, **Google Sheets**, and **Twilio WhatsApp API**.

The workflow automates customer interactions by collecting enquiry details, storing them in Google Sheets, and sending an instant WhatsApp confirmation message.

---

## Architecture

```
Customer
   │
   ▼
AI Chat Interface
   │
   ▼
Google Gemini AI
   │
   ▼
Data Extraction
   │
   ▼
Google Sheets
   │
   ▼
Twilio WhatsApp API
   │
   ▼
Customer Confirmation
```

---

## Features

- AI-powered customer interaction
- Workflow automation using n8n
- Automatic lead collection
- Google Sheets integration
- WhatsApp confirmation messages
- Zero manual data entry
- Easy to customize for any business

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Google Gemini AI | Natural Language Processing |
| Google Sheets | Data Storage |
| Twilio WhatsApp API | Customer Notifications |

---

## Workflow

```
Customer Chat
      │
      ▼
Google Gemini AI
      │
      ▼
Collect Customer Information
      │
      ▼
Store Data in Google Sheets
      │
      ▼
Send WhatsApp Confirmation
```

---

## Project Structure

```
AI-Customer-Enquiry-Automation/

├── workflow.json
├── README.md
├── images/
│   ├── workflow.png
│   ├── chatbot.png
│   ├── google-sheet.png
│   └── whatsapp-message.png
└── LICENSE
```

---

## Screenshots

### Workflow
<img width="940" height="381" alt="image" src="https://github.com/user-attachments/assets/6b483be8-0b36-45f5-9103-6cbe4c234bfe" />

---
### Google Sheets Database

<img width="400" height="308" alt="image" src="https://github.com/user-attachments/assets/40167c79-fc86-4845-81e6-3b73dfba0996" />
<img width="400" height="129" alt="image" src="https://github.com/user-attachments/assets/c7032864-e9c5-44f5-9999-365c9d2e947c" />

---

### WhatsApp Confirmation

<img width="400" height="450" alt="image" src="https://github.com/user-attachments/assets/28de7bb3-08bf-4972-aff0-d115286906bc" />


---

## How It Works

1. Customer initiates a conversation.
2. Google Gemini AI processes the request.
3. The AI collects:
   - Name
   - Phone Number
   - Email Address
   - Requirement
4. Customer information is automatically stored in Google Sheets.
5. Twilio sends an instant WhatsApp confirmation message.
6. The enquiry is successfully recorded for future follow-up.

---

## Business Value

- Reduces manual effort
- Improves response time
- Centralizes customer enquiries
- Automates lead management
- Enhances customer experience
- Provides scalable workflow automation

---

## Future Improvements

- Appointment booking
- Email notifications
- CRM integration
- Multi-language support
- Retrieval-Augmented Generation (RAG)
- Analytics dashboard
- Voice-based customer support
- Live human handoff

---

## Installation

### Prerequisites

- n8n
- Google Gemini API Key
- Google Sheets API Credentials
- Twilio Account
- WhatsApp Sandbox

### Setup

1. Clone the repository.

```bash
git clone https://github.com/divaaasharma/ai-customer-enquiry-automation.git
```

2. Import `workflow.json` into n8n.

3. Configure:
   - Google Gemini Credentials
   - Google Sheets Credentials
   - Twilio Credentials

4. Execute the workflow.

5. Test using the n8n Chat interface.

---

## Sample Workflow

```
Customer
   │
   ▼
Chat Trigger
   │
   ▼
AI Agent
   ├──────── FAQ
   ├──────── Services
   └──────── Customer Enquiries
                 │
                 ▼
         Google Sheets
                 │
                 ▼
       Twilio WhatsApp API
                 │
                 ▼
       Confirmation Message
```

---

## Repository Contents

| File | Description |
|------|-------------|
| workflow.json | Complete n8n workflow |
| README.md | Project documentation |
| images/ | Workflow screenshots |
| LICENSE | License file |

---

## Author

**PRATIK SHUBHAM**

MBA (Artificial Intelligence & Data Science)

GitHub: https://github.com/divaaasharma

---

## License

This project is released under the MIT License.

---

### If you found this project useful, consider starring the repository.
