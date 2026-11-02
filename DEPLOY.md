# Deploying this site (free, public link)

Any of these work well for a static site like this. GitHub Pages is the most common choice for developer portfolios specifically, since it also signals you know Git.

## Option 1: GitHub Pages (recommended for a dev portfolio)
1. Create a new GitHub repo, e.g. `yourusername.github.io` (using this exact name gives you the cleanest URL: `https://yourusername.github.io`). A different repo name still works, just at `https://yourusername.github.io/repo-name`.
2. Push these files (`index.html`, `styles.css`, `script.js`, `assets/`) to the repo's root.
3. In the repo, go to Settings > Pages, set the source branch to `main` (or `master`), folder `/root`.
4. Wait 1-2 minutes, then visit the URL GitHub gives you.

## Option 2: Netlify
1. Go to netlify.com, sign in, and drag-and-drop the whole `portfolio` folder onto the dashboard.
2. Netlify gives you a live URL immediately (something like `random-name-123.netlify.app`).
3. You can rename the subdomain for free in Site settings, or attach a custom domain later.

## Option 3: Vercel
1. Go to vercel.com, sign in, and use "Add New Project" > drag-and-drop or connect a GitHub repo.
2. Vercel deploys it and gives you a live URL.

## After deploying
- Test the live link on your phone, not just your laptop.
- Send yourself a test email/LinkedIn message with the link to confirm the preview card (title, description) shows correctly.
- Keep the link short and memorable if possible — this is what goes on your CV/resume.
