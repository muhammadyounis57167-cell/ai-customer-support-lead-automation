# Database Schema (MongoDB Atlas)

## Collection: customers
- customer_id (string, unique)
- name (string)
- email (string)
- first_contact_date (date)
- status (new / active / lead / resolved)

## Collection: conversations
- conversation_id (string, unique)
- customer_id (string, ref: customers)
- email_subject (string)
- email_body (string)
- ai_classification (complaint / question / sales_lead)
- ai_reply (string)
- lead_score (hot / warm / cold / none)
- status (pending_approval / sent / resolved)
- timestamp (datetime)
