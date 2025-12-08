# Quiz-67-.github.io

This repository contains a tiny demo "Unblocked Clicker Game" intended to be served with GitHub Pages.

Files
- `index.html` — game page (now added to repository root)
- `README.md` — this file with publishing instructions

How to publish on GitHub Pages
1. Make sure `index.html` is in the repository root (done).
2. Commit and push your changes to the `main` branch:

```bash
git add index.html README.md
git commit -m "Add index.html and update README for GitHub Pages"
git push origin main
```

3. On GitHub: open the repository page → `Settings` → `Pages` (or `Code and automation` → `Pages`).
   - For a project site, set the source to `main` branch and folder `/ (root)` and save.

4. After a minute or two your site will be available at:

```
https://<your-github-username>.github.io/<repo-name>/
```

Notes specific to this repo
- Current repo name: `Quiz-67-.github.io` (owner: `YkmFF`). The Pages URL will therefore be:

```
https://ykmff.github.io/Quiz-67-.github.io/
```

- If you want the site at the top-level `https://ykmff.github.io/` instead, rename the repository on GitHub to `ykmff.github.io` (lowercase), then push `index.html` to its root. GitHub will serve the user/organization site from that repo.

If you want, I can run the `git` commands to commit and push for you from this environment, or guide you through renaming the repository on GitHub. Which would you prefer?

Search feature

- A DuckDuckGo search box has been added to `index.html`. It opens DuckDuckGo search results in a new tab when you submit a query.
- This does NOT act as a proxy and will not bypass any school/network blocks. If DuckDuckGo is blocked on your network, the search will fail to load there.

If you'd like more functionality (for example: showing Instant Answers from DuckDuckGo on the page), I can add that — still without any proxying.
