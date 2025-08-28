READY-TO-USE PACKAGE (Netlify Forms Enabled)

FILES
- index.html      : Landing page with Netlify Form (name="signup").
- thankyou.html   : Redirect destination after form submit.
- sample_leads.csv / sample_leads.json : Example data (optional).

HOW TO DEPLOY
1) Go to https://app.netlify.com/drop
2) Drag & drop this whole ZIP (or the folder) to deploy.
3) Netlify gives you a live URL instantly.

ENABLE & TEST FORMS
1) Open your live site URL in a browser.
2) Enter an email in the form and submit.
3) It will redirect to /thankyou.html.
4) In Netlify dashboard: Site → Forms → 'signup' should appear with your submission.

EMAIL NOTIFICATIONS (optional)
- Netlify → Site → Forms → signup → Notifications → Add notification → Email → enter your address.

EXPORT LEADS
- Netlify → Site → Forms → signup → 'Export CSV' to download all entries.

TIPS
- If you change the form name, also change the hidden input value form-name to match.
- Keep 'action="/thankyou.html"' to show the thank you page after submit.
