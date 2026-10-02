# 90 Days to Become an AI Engineer
Developed and updated by **Mahendra Singh**.

```
index.html      the whole website (one file)
api/chat.js     AI tutor backend (Vercel serverless function)
package.json
```

## Deploy on Vercel (recommended, needed for the AI tutor)
1. Push this folder to a GitHub repo and import it in Vercel (or run `vercel` inside the folder).
2. Vercel → Project → Settings → Environment Variables, add:
   - `ANTHROPIC_API_KEY` = your key from https://console.anthropic.com
   - optional `ANTHROPIC_MODEL` (default `claude-haiku-4-5-20251001`, the cheapest)
   - optional `DAILY_LIMIT_PER_IP` (default 60 questions per student per day)
3. Redeploy. The "Ask AI tutor" button now answers students.

Set a monthly spend limit in the Anthropic console so student usage can't exceed your budget.

## Without Vercel
Opening `index.html` directly (or on Netlify / GitHub Pages) works for everything except the AI tutor, which will show a "not connected" message.

## How students use it
1. Enter name + start date, then lock it. Weeks, ship dates and the 92-day tracker count from that date.
2. Progress is saved in their own browser. "Progress code" moves it to another device.
3. Ask AI tutor (bottom-right) for doubts in English or Hinglish. It knows their current week.

Roadmap content based on "90 Days to Become an AI Engineer: The Oct → Dec Roadmap" by Sakshi Jaiswal (AI in Plain English).
