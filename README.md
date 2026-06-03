# Sam's Nutrition Tracker 🌸

A personal AI-powered nutrition, activity & wellness tracker.

## Features
- 📸 Photo meal logging — snap & AI identifies macros
- 🏃 Activity & movement tracker (walks, gym, dance, travel)
- 📈 Weekly charts — calories, protein, weight trend
- 🎯 Weekly goal editor with quick-pick presets
- 💧 Water & mood tracker
- 💬 AI coach with words of affirmation
- 📱 PWA — works as a phone app (Add to Home Screen)

## Setup & Deploy to Vercel (10 min!)

### Step 1 — Get your Anthropic API key
1. Go to https://console.anthropic.com
2. Click "API Keys" → "Create Key"
3. Copy the key (starts with `sk-ant-...`)

### Step 2 — Push to GitHub
```bash
cd sam-tracker
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/sam-tracker.git
git push -u origin main
```

### Step 3 — Deploy on Vercel (free!)
1. Go to https://vercel.com → Sign up with GitHub
2. Click "Add New Project"
3. Select your `sam-tracker` repo
4. In **Environment Variables**, add:
   - `ANTHROPIC_API_KEY` = your key from Step 1
5. Click **Deploy** — done! 🎉

### Step 4 — Add to your iPhone home screen
1. Open your Vercel URL in Safari
2. Tap the Share button (square with arrow)
3. Tap "Add to Home Screen"
4. Name it "Sam's Tracker" → Add

It'll appear as an app icon on your home screen! 🌸

## Local development
```bash
npm install
# Add your API key to .env.local
npm run dev
# Open http://localhost:3000
```
