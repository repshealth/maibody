# MAI Body

Waitlist landing page for the new MAI Body website.

- `index.html` landing page with the waitlist form (name, email, phone)
- `thank-you.html` shown after a successful signup
- `styles.css` shared styles
- `images/` photography

## Connecting the form

Set `WAITLIST_ENDPOINT` near the top of the script in `index.html` to your form handler (MailerLite, Zapier, GHL webhook etc.). The form POSTs JSON `{ name, email, phone }` there, then sends the visitor to `thank-you.html`. Left empty, it skips straight to the thank-you page.
