# ai-customer-support-lead-automation
AI-powered customer support and lead automation SaaS using n8n, FastAPI, AI agents, and a production-ready web dashboard.
# AI Customer Support + Lead Automation SaaS

An AI-powered platform that helps businesses automatically handle
customer emails, classify conversations, identify leads, generate
AI responses, and manage follow-ups.

## Planned Features

- AI customer email classification
- Automatic customer support responses
- Lead detection and scoring
- Automated follow-ups
- Human approval workflow
- Customer/lead database
- Analytics dashboard
- n8n workflow automation
- FastAPI backend
- Authentication
- Production deployment

## Tech Stack

- Python
- FastAPI
- n8n
- AI/LLM
- Database
- React
- GitHub
- Cloud deployment

## Status

🚧 Initial development
## System Architecture

1. Gmail receives customer emails
2. n8n triggers on new email and filters spam
3. AI (Google Gemini) classifies email into Sales, Support, or Complaint
4. AI sentiment/priority detection flags urgent issues
5. Category-specific AI generates a professional reply
6. Email data is logged into a structured database (Google Sheets initially, PostgreSQL in future)
7. Urgent/high-risk emails trigger a Telegram alert
8. (Future) Admin dashboard displays analytics and conversation history

## Current Progress

- [x] Basic email automation working (n8n + Gmail + Gemini)
- [x] AI classification (Sales/Support/Complaint)
- [ ] Sentiment/priority detection
- [ ] Telegram alerts
- [ ] Database upgrade (PostgreSQL)
- [ ] Admin dashboard
- [ ] Authentication
- [ ] Production deployment
