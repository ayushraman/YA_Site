# YA. Portfolio

An interactive, creative portfolio website featuring custom animations, 2D physics, interactive music player, drawing canvas, and pixel-perfect design.

## Project Structure

```
├── index.html          # Main entry point for Vercel and web servers
├── ya-portfolio.html   # Standalone copy for local viewing
├── vercel.json         # Vercel deployment configuration (clean URLs, rewrites & headers)
└── .gitignore          # Git ignore file
```

## Running Locally

You can preview the site locally using any static web server:

```bash
# Using Python
python -m http.server 3000

# Using Node / npx
npx serve .
```

Then open `http://localhost:3000` in your browser.

You can also simply open `index.html` or `ya-portfolio.html` directly in any web browser or via VS Code Live Server.

## Deploying to Vercel

This repository is pre-configured and ready for zero-config deployment on Vercel:

1. Push your changes to GitHub:
   ```bash
   git add .
   git commit -m "Make site deploy-ready for Vercel"
   git push origin main
   ```
2. In the [Vercel Dashboard](https://vercel.com/new), import this repository.
3. Keep default settings (Framework Preset: **Other**, Build Command: empty, Output Directory: empty).
4. Click **Deploy**.

Vercel will automatically serve `index.html` at your root domain (`/`), and `vercel.json` ensures `/ya-portfolio` routes seamlessly as well.
