# AI Ticket Triage System

An AI-powered automation workflow that classifies customer support tickets using LLMs and structured JSON responses.

## Features
- Webhook-based API endpoint
- AI ticket summarization
- Urgency classification
- Department routing
- Structured JSON outputs

## Tech Stack
- n8n
- Groq/OpenAI API
- Webhooks
- Postman

## Workflow Architecture

Webhook → AI Processing → Structured Response

## Example Input

```json
{
  "ticket": "Customer cannot access account after payment."
}
```

## Example Output

```json
{
  "Summary": "Customer unable to access account after successful payment.",
  "Urgency": "Medium",
  "Department": "Technical Support"
}
```

## Future Improvements
- Database logging
- Slack integration
- Email notifications
- CRM integration
