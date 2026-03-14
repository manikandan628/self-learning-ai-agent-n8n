# Self Learning AI Agent (n8n)

This project is a self-learning AI Telegram assistant built using **n8n workflows**.

The agent can:
- Accept text and voice messages from Telegram
- Transcribe audio messages
- Use an LLM (Groq) to generate responses
- Store user memories in Google Sheets
- Use those memories to provide context-aware replies

## Features

• Telegram chatbot  
• Voice transcription  
• Memory system using Google Sheets  
• AI Agent with Groq LLM  
• Context-aware responses  

## Workflow Architecture

Telegram → n8n → AI Agent → Memory → Response

## Technologies Used

- n8n
- Groq LLM
- Google Sheets
- Telegram Bot API
- Gemini for transcription

## Setup

1. Install n8n
2. Import `workflow.json`
3. Add credentials:
   - Telegram Bot API
   - Groq API
   - Google Sheets API
   - Gemini API

4. Run the workflow

## Use Case

This agent learns about the user over time by storing memories and using them in future conversations.

Example:

User: "My name is Alex"  
Agent stores memory → "User name is Alex"

Later:

User: "What is my name?"  
Agent responds → "Your name is Alex."

## Author

Manikandan K
