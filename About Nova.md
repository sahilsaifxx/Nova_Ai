Nova AI Chatbot by Sahil 
AI-powered chatbot built with React + Cloudflare Workers + Google Gemini API

Nova AI is a modern, fast, and privacy-focused chatbot where you can ask anything. Powered by Google Gemini, it uses a React frontend and a Cloudflare Worker backend to keep your API key secure and avoid CORS issues.
Features 
• Gemini API Integration: Uses Google Gemini 3.5 Flash-lite, 3.6 Flash and 3.1 Pro for smart, contextual responses 
• Secure Proxy: Cloudflare Worker hides your API key — no direct calls from the browser 
• React Frontend: Clean, responsive UI built with HTML + CSS + JavaScript
• Real-time Chat: Streams responses like ChatGPT for a smooth experience 
• Lightweight: Fast load times with minimal dependencies  Tech Stack

## Tech Stack

**Frontend**
- React 
- HTML5
- CSS3
- JavaScript ES6+

**Backend**
- Cloudflare Workers
- JavaScript/TypeScript

**AI Model**
- Google Gemini API Key

**Deployment**
- Cloudflare Pages
- Cloudflare Workers
  
How It Works 
1. User sends a message from the React frontend
2. Request goes to the Cloudflare Worker proxy
3. Worker securely calls Gemini API using an environment variable
4. Response streams back to the frontend in real time

   CLICK BELOW LINK TO RUN NOVA AI
   https://sahilsaifxx.github.io/Nova_Ai/
