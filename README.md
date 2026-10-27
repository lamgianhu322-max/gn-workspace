# Như’s Personal Workspace

A static personal study workspace published with GitHub Pages. The existing website is in `outputs/index.html`; no build step is required.

## Deploy with GitHub Pages

The repository must contain `outputs/index.html` and `.github/workflows/pages.yml`.

1. Push the repository’s `main` branch to GitHub.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source.
3. Open **Actions** and wait for **Deploy personal workspace to GitHub Pages** to complete successfully.
4. Find the published URL in the workflow deployment summary or under **Settings → Pages**. For a project site it is usually `https://<owner>.github.io/<repository>/`; a repository named `<owner>.github.io` uses `https://<owner>.github.io/`.

The included workflow publishes the contents of `outputs/` on every push to `main`. It can also be started manually from the Actions tab with **Run workflow**.

## Local preview

Open `outputs/index.html` in a web browser. The workbench does not need a server or package installation for normal use.

## Update the website

Edit `outputs/index.html`, commit the change, and push it to `main`. GitHub Actions will publish the new version automatically after the deployment workflow succeeds.

Tasks, notes, study records, and reflections are saved in each visitor’s browser storage. They are not shared between visitors or synced to GitHub. Progress figures in the page are demo data.
