<<<<<<< HEAD
# Shiv Gopal Dixit Advocate & RC Legal Associate — Website

A single-page, self-contained static website. All HTML, CSS and JavaScript
(including the disclaimer gate, scroll animations, and dark-mode support)
live in one file: `index.html`. The only external resources are Google
Fonts (Lora and Work Sans), loaded via `<link>` tags in the `<head>`.

## Folder structure

```
rc-legal-associate-website/
├── index.html      # the entire website (HTML + CSS + JS, self-contained)
├── vercel.json      # static hosting config for Vercel
└── README.md         # this file
```

## Deploy to Vercel

### Option A — Vercel CLI
1. Install the CLI if you don't have it: `npm install -g vercel`
2. From inside this folder, run:
   ```
   vercel
   ```
3. Follow the prompts (choose "Other" as the framework preset, or let
   Vercel auto-detect a static site — no build step is required).
4. Run `vercel --prod` to publish to your production URL.

### Option B — Vercel dashboard (no CLI)
1. Push this folder to a new GitHub/GitLab/Bitbucket repository.
2. Go to https://vercel.com/new and import that repository.
3. Framework preset: "Other" (static). Build command: none. Output
   directory: leave as root (`.`).
4. Click Deploy.

### Option C — Drag and drop
1. Go to https://vercel.com/new
2. Drag the `rc-legal-associate-website` folder onto the page.
3. Deploy — no configuration needed since it's a single static HTML file.

No environment variables, build steps, or dependencies are required.
=======
# shiv-gopal-dixit-website
Shiv Gopal Dixit Advocate &amp; RC Legal Associate
>>>>>>> fd91eb2c52bf0a941d41e66c1d76160c178eda51
