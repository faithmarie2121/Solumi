# Solumi website

Static website for Solumi's public homepage, changelog, Terms of Service, and Privacy Policy.

## Setup
1. Create a public GitHub repository named `solumi`.
2. Upload `index.html`, `updates.html`, `terms.html`, `privacy.html`, and `style.css` to the repository root.
3. In Settings > Pages, choose Deploy from a branch, branch `main`, folder `/(root)`. Save.
4. Your site should appear at `https://YOUR-USERNAME.github.io/solumi/`.
5. Replace EVERY placeholder (search for `[`), especially in privacy.html, and validate statements against actual code before publishing the URLs to Discord.

## Add updates
Edit `updates.html` in GitHub, insert a new `<section class="tile">...</section>` above older entries, and commit changes.

## Security
This public repository is ONLY for website files. Never upload bot code, `.env`, Discord bot tokens, database secrets, or backups.
