# Manish Bijarniya — Portfolio

This folder contains the single-page portfolio ready for GitHub Pages.

## Publish with GitHub CLI

Run these commands in PowerShell from this folder. Git, GitHub CLI (`gh`), and a GitHub CLI login are required.

```powershell
gh auth login
git init -b main
git add index.html .nojekyll
git commit -m "Publish portfolio"
gh repo create manishbijarniya0112.github.io --public --source=. --remote=origin --push
```

Then open the repository's **Settings → Pages** and choose **Deploy from a branch**, branch **main**, folder **/(root)**, and **Save**. GitHub Pages will publish the site at:

`https://manishbijarniya0112.github.io`

Publishing source setup is described in the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
