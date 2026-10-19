# YouTube Channel Auditor, created by Himz91

A static, single-page app. No build step, no server, no environment variables.
Each visitor enters their own free YouTube Data API key, which stays in their browser.

## Deploy with GitHub (recommended)
1. Create a new GitHub repository and upload these files (index.html, vercel.json).
2. In Vercel, click Add New, then Project, and import the repository.
3. Framework Preset: Other. Leave Build Command and Output Directory empty. Click Deploy.
4. Every later push to the main branch redeploys automatically.

## Deploy with the Vercel CLI
    npm i -g vercel
    cd this-folder
    vercel          # first deploy, answer the prompts (framework: Other)
    vercel --prod   # publish to your production URL

## Notes
- Vercel's free Hobby plan is for personal, non-commercial use only.
- Never put your own API key in index.html. Visitors paste theirs into the page.
