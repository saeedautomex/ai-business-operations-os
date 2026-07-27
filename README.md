# AI Business Operations OS

An AI-powered business automation system built with n8n and OpenAI.

## Features

- AI-powered request classification
- Sales routing
- Customer support routing
- Operations routing
- Document intelligence routing
- Human review escalation
- Priority detection
- Webhook-based architecture

## Architecture

Webhook
↓
Normalize Request
↓
Master AI Router
↓
AI Decision Parser
↓
Department Router
├── Sales
├── Support
├── Operations
├── Document Intelligence
└── Human Review

## Tech Stack

- n8n
- OpenAI
- Webhooks
- AI Automation
- JSON

## Setup

1. Import the workflow into n8n.
2. Add your own OpenAI credentials.
3. Activate the workflow.
4. Send a request to the webhook.
