# AI-Powered Calendar Enrichment System

Automatically syncs UFC events, concerts, and comedy shows to Google Calendar with AI-generated insights.

## 🔧 Technologies Used
- **n8n** (Workflow automation)
- **OpenAI GPT-3.5** (Event enrichment)
- **ScrapingBee** (Web data extraction)
- **Google Calendar API**
- **Notion API**

## 🚀 Features
- Smart event color-coding by location
- AI-generated summaries and context
- Multi-platform sync (Google Calendar + Notion)

## ⚙️ Setup Guide
1. Import `workflow.json` to n8n
2. Configure these environment variables:
   - `OPENAI_API_KEY`
   - `GOOGLE_CALENDAR_CREDENTIALS`
3. Activate all API nodes

[![n8n](https://img.shields.io/badge/n8n-%23000000.svg?logo=n8n&logoColor=white)](https://n8n.io/)
