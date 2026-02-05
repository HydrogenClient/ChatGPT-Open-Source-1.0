# ChatGPT Open-Source 1.0

**ChatGPT OS 1.0** is a high-performance, open-source AI assistant built from GGUF models and fully customizable open-source tools. It can run **locally** with your own backend or entirely in the browser for demo purposes.

---

## Features

- ✅ **Local or API-powered AI**: Connect your frontend to a FastAPI backend running your GGUF model for real AI responses.  
- ✅ **Interactive chat interface**: User and AI messages in a simple, lightweight browser interface.  
- ✅ **Frontend-only demo available**: Simulated responses let you test the UI without Python or a backend.  
- ✅ **Future-ready**: Ready to extend with per-user API keys, rate limits, offline support, and improved UI styling.  

---

## Getting Started

### Demo Mode (No Backend)
1. Clone or download this repository.  
2. Open `index.html` in your browser.  
3. Type a message and click **Send**.  
4. ChatGPT OS 1.0 will reply with simulated AI responses.  

### API Mode (Real AI)
1. Run your FastAPI backend locally or on a server:

```bash
uvicorn app:app --host 0.0.0.0 --port 8000
