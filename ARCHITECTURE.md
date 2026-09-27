# System Architecture

## Flow
Gmail → n8n → AI Agent → Decision → Database → Dashboard

## Components

### 1. Gmail (Input)
- New email trigger

### 2. n8n (Orchestration)
- Receives email
- Sends to AI Agent
- Routes based on AI response

### 3. AI Agent
- Classifies: complaint / question / sales lead
- Drafts reply
- Scores leads (hot/warm/cold)

### 4. Database
- Stores customer records
- Stores conversation history
- Stores lead scores

### 5. Dashboard
- Shows email stats
- Shows leads list
- Shows reply history
