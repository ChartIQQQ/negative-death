# Negative Death

Static site. No build step. Entry point: `index.html`.

## Deploy to Vercel

Option A: GitHub
1. Create a new GitHub repo and upload these files to the root.
2. In Vercel: Add New > Project > import the repo.
3. Framework Preset: Other. Leave Build Command and Output Directory empty. Deploy.

Option B: CLI
1. `npm i -g vercel`
2. From this folder run `vercel`, then `vercel --prod`.
