# PomodoroPhone

Glassmorphism Pomodoro timer with iOS design, ASCII art clock, session todo list, and cookie persistence.

## Deploy to Render

### One-click (Blueprint)

1. Push this repo to GitHub
2. In Render dashboard → **Blueprint** → connect your repo
3. Render reads `render.yaml` and deploys automatically

### Manual (Static Site)

1. In Render dashboard → **New +** → **Static Site**
2. Connect your GitHub repo
3. Set:
   - **Build Command:** `echo "no build step"`
   - **Publish Directory:** `.`
4. **Deploy**

No build step required — it's a single `index.html`.