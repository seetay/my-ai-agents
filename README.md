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

### 🎯 3. Autonomous SDR Agent (SDR Agent.json)(Web_Scraper.json, AI_Lead_Processor.json, Cold_Emailer.json)

**Stack:** n8n + Custom Web Scraping + OpenAI API **Function:**

- Autonomously scrapes target company directories to extract B2B decision-maker data.
- Uses LLM logic to analyze lead profiles and draft hyper-personalized outreach emails.
- Automates the entire outbound prospecting pipeline without human intervention.

## 🚀 How to Use This Workflow
1. **Download:** Click on `Curator Agent.json` above and download the file (or copy the raw text).
2. **Import to n8n:**
   - Open your n8n dashboard.
   - Click **"Add Workflow"** (top right).
   - Click the **three dots (...)** in the top right corner -> **"Import from File"**.
   - Select the JSON file you just downloaded.
3. **Setup Credentials:**
   - Open the **HTTP Request** node and add your YouTube API Key.
   - Open the **AI Agent** node and add your Groq API Key.
   - Open the **Telegram** node and add your Chat ID.
4. **Run:** Toggle the workflow to **Active**.
