# n8n - Automated YouTube Shorts Workflow

## 🔥 Deploy to Render

1. Fork this repo
2. Go to [https://dashboard.render.com](https://dashboard.render.com)
3. Click “New Web Service”
4. Select your fork
5. Confirm Render detects `Dockerfile`
6. Add environment variables as per `.env.example`
7. Done ✅

## 💡 Workflow

Automates:
- Fetching videos from Google Drive
- Caption generation using Hugging Face
- Upload to YouTube Shorts
- Quota control (6/day)
