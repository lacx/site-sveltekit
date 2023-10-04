# site-svelte

### Create SvelteKit Project

 1 - Created new project from GitHub (README.md, LICENSE only)

 2 - Initialize New Codespace from GitHub.com 

 3 - Create a SvelteKit project with vite in GitHub Codespaces

```bash
npm init vite
```
- installs create-vite@4.4.1 (y)
- set project name (site-vite-project)
- select Svelte/SvelteKit/SvelteKit demo app/TypeScript, JavaScript (project is created)
```bash
  1: cd site-vite-project
  2: npm install (or pnpm install, etc)
  3: git init && git add -A && git commit -m "Initial commit" (optional)
  4: npm run dev -- --open
```

### Create GitHub Action to deploy the site to GitHub Pages

- In the GitHub repo go to _Settings/Pages_ at _Source_ select __GitHub Actions__ and click _create your own_

- see the file _.github\workflows\deploy-to-gh-pages_