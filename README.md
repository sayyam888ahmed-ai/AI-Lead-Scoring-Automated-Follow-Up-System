# AI Lead Scoring & Automated Follow-Up System

An AI-powered workflow built with n8n that analyzes incoming B2B leads, assigns a lead score, classifies leads as Hot, Warm, or Cold, stores the results in Google Sheets, and automatically sends follow-up emails to Hot leads.

## 🚀 Workflow

Webhook
→ Edit Fields
→ OpenAI
→ Format AI Result
→ Google Sheets
→ IF
→ Gmail

## ✨ Features

- Receive lead data through Webhook
- AI-powered lead analysis
- Lead Score from 0–100
- Hot / Warm / Cold classification
- Lead quality assessment
- Recommended sales action
- Automated follow-up message
- Store lead analysis in Google Sheets
- Automatically email Hot leads

## 🛠️ Technologies Used

- n8n
- OpenAI
- Google Sheets
- Gmail
- Webhooks
- Postman

## 📊 Lead Classification

| Score | Classification |
|------:|----------------|
| 80–100 | Hot |
| 50–79 | Warm |
| 0–49 | Cold |

## 🔄 How It Works

1. Lead information is received through a webhook.
2. n8n sends the lead information to OpenAI.
3. OpenAI analyzes the lead and generates a score and classification.
4. The AI result is formatted into structured fields.
5. The lead and analysis are saved in Google Sheets.
6. An IF condition checks whether the lead is Hot.
7. Hot leads automatically receive a follow-up email through Gmail.

## 📁 Project Structure

```text
ai-lead-scoring-follow-up/
├── README.md
├── day-13-ai-lead-scoring.json
└── screenshots/
