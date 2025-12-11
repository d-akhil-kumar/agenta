# Slack Chat Summarizer (NestJS + OpenAI)

A Slack plugin built with **NestJS** and **OpenAI** that summarizes chat history based on a time duration using a Slash Command. 

## Features
- **Slash Command:** `/summarize [time]` (e.g., "2 hours ago", "since 9am", "30m").
- **AI Power:** Uses OpenAI (GPT-3.5/4) to generate concise summaries.
- **Smart Parsing:** Uses `chrono-node` to understand natural language dates.

## Prerequisites
- Node.js (v16+)
- A Slack App created at [api.slack.com](https://api.slack.com/apps)
- An OpenAI API Key

## Installation

```bash
# 1. Install dependencies
npm install

# 2. Create environment file
cp .env.example .env