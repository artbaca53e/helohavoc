# helohavoc deployment

## Cloudflare Pages
This site is a static Cloudflare Pages project.

### Pages structure
- `/` -> home
- `/mealplan/` -> meal plan builder
- `/dashboard/` -> dashboard
- `/tools/` -> tools launcher
- `/rc/` -> RC workspace
- ### Source files
- `index.html`
- `styles.css`
- `mealplan/index.html`
- `dashboard/index.html`
- `tools/index.html`
- `rc/index.html`
- `404.html`
- `_routes.json`

### Local development
Edit the HTML files directly.

### Deployment
1. Commit changes to GitHub.
2. Cloudflare Pages auto-deploys from the repo.
3. Use the custom domain in Cloudflare DNS.

### Notes
- RC page uses browser localStorage for saved entries.
- This is a static starter; backend/API work can be added later.
