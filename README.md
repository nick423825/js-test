# JavaScript sample app

A browser greeting app with no npm dependencies.

## Run locally

Run `npm start`, then open http://localhost:3000.

## Edit and run online

On GitHub, open **Code → Codespaces → Create codespace on main**.
The development container includes Node.js and starts the app automatically.
Open the forwarded port 3000 from the **Ports** panel if the browser does not open.
If you stop the app, run `npm start` to restart it.

## Public website

In the repository, open **Settings → Pages** and choose **GitHub Actions** as
the source. The deployment workflow publishes `index.html` on pushes to `main`.
For the first deployment, open **Actions → Deploy browser app → Run workflow**.
The deployed URL appears in the workflow and in **Settings → Pages**.

The public website hosts the browser app directly. The Node.js server is used
for development only. Codespaces usage and Pages availability depend on your
GitHub account and repository settings.

## Codex Cloud (optional)

Once this project is on GitHub, choose **Work in → Cloud → Select environment
→ Create environment** in ChatGPT on the web or desktop. Connect GitHub, select
the repository, review the setup, and publish the environment.

Codex Cloud runs coding tasks remotely; use GitHub Pages for the public website
and Codespaces for an interactive development terminal and browser preview.
