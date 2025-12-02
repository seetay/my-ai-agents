# AI Automation Agents

This repository contains my production-ready AI agents built with n8n, Llama 3, and Python.

## 🤖 1. Commerce Price Bot (Price Bot.json)
**Stack:** Telegram API + Tavily Search + Llama 3
**Function:**
- Autonomously searches for product prices.
- Handles user queries via Telegram interface.

## 📺 2. YouTube Curator Agent (Curator Agent.json)
**Stack:** YouTube Data API + Groq (Llama 3) + n8n Schedule
**Function:**
- Runs daily at 10:00 AM.
- Filters out "Shorts" and clickbait using Regex logic.
- Adds high-quality educational videos to a private playlist automatically.
