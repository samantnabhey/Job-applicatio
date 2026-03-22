# job.pipeline

4-step automated job application pipeline built with React + Claude AI.

## Setup

\`\`\`bash
npm install
cp .env.example .env.local
# Fill in your API keys in .env.local
npm run dev
\`\`\`

## Deploy to Vercel

\`\`\`bash
npm install -g vercel
vercel
\`\`\`

Then add environment variables in Vercel dashboard → Settings → Environment Variables.

## API Keys

- **Adzuna**: free at https://developer.adzuna.com
- **JSearch**: free tier at https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch

## Local Playwright Bot (Step 4)

\`\`\`bash
pip install playwright anthropic
playwright install chromium
python auto_apply.py
\`\`\`
