# AI Chatbot

## What I Built
A minimal AI chatbot with a Node.js Express backend and a vanilla JS frontend.

## API and Model
**API:** OpenRouter  
**Model:** openai/gpt-4o-mini

**Why backend only:** API keys exposed in frontend JavaScript are readable by anyone who opens browser DevTools. The API key is therefore kept securely in the backend.

**Fallback provider:** Google Gemini API (free tier). Switching requires changing the base URL.

## Live Deployment
**Frontend:** https://sparkling-dango-8b3b66.netlify.app/  
**Backend:** https://ai-chatbot-challenge-1-11-1.onrender.com/
