# Kwality Restaurant — GitHub Pages Ready

Static website package. No npm, Node.js, Vite or build step is required.

## GitHub Pages
1. Create/open a GitHub repository.
2. Upload **all files and folders in this package to the repository root**.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save and wait for GitHub Pages to deploy.

## Important
Keep the folder structure unchanged:
- `index.html`
- `css/style.css`
- `js/app.js`
- `js/data.js`
- `images/*`
- `.nojekyll`

The site uses relative asset paths, so it works in a project repository such as:
`https://USERNAME.github.io/REPOSITORY/`

The reservation form is frontend-only and prepares a WhatsApp message; it does not store bookings on a server.
