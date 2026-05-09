# Omni-Skill

Omni-Skill is a static single-page concept document for a career evidence layer that translates verified gaming, esports, and online community activity into professional proof.

## Project files

- `omni-skill.html` is the main page.
- `index.html` is a lightweight root entry file for static hosts.
- `netlify.toml` tells Netlify to publish the repository root and serve `omni-skill.html` at the site root.

## Run locally

Open `index.html` or `omni-skill.html` directly in a browser. No build step, package install, or local server is required.

## Deploy on Netlify from GitHub

1. Push this repository to GitHub.
2. In Netlify, choose **Add new project** and then **Import an existing project**.
3. Connect GitHub and select `tfthushaar/Omni-Skill`.
4. Use these build settings:
   - Build command: leave empty
   - Publish directory: `.`
5. Deploy the site.

After the site is connected, future pushes to the `main` branch will trigger new Netlify deploys.

Netlify references:

- [Deploy from your repository](https://docs.netlify.com/start/quickstarts/deploy-from-repository/)
- [Build configuration overview](https://docs.netlify.com/build/configure-builds/overview/)
- [Create deploys with Netlify CLI](https://docs.netlify.com/deploy/create-deploys/)

## Optional Netlify CLI deploy

If you prefer deploying from the terminal:

```bash
npm install -g netlify-cli
netlify deploy --prod --dir=.
```

Run those commands from the repository root.

## Notes

- This is a static HTML site.
- The page uses Google Fonts from the browser at runtime.
- There are no Node, React, Vite, or backend dependencies.
