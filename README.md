# CUET College Advisor

An AI-powered app that recommends colleges and courses based on your CUET scores, category, location, and preferences. Powered by **Google Gemini** (free, no credit card needed).

## Deploy to Vercel (free, 5 minutes)

### 1. Push this repo to GitHub
Upload all files maintaining this structure:
```
your-repo/
├── index.html
├── vercel.json
├── README.md
└── api/
    └── chat.js
```

### 2. Get a free Gemini API key
1. Go to [aistudio.google.com](https://aistudio.google.com)
2. Sign in with your Google account
3. Click **"Get API Key"** → **"Create API key"**
4. Copy the key — it's completely free, no card required

### 3. Connect repo to Vercel
1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **"Add New Project"** → import your repo
3. Click **Deploy**

### 4. Add your Gemini API key to Vercel
1. In your Vercel project → **Settings → Environment Variables**
2. Add:
   - **Name:** `GEMINI_API_KEY`
   - **Value:** your key from AI Studio
3. **Save** → go to **Deployments** → **Redeploy**

Your app is now live at `https://your-project.vercel.app` 🎉

> Your API key is stored securely server-side — never exposed to users.
