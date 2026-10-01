# Vocto website

A responsive pre-launch site for Vocto, built with Hugo and ready for GitHub Pages.

## Run locally

1. Install [Hugo Extended](https://gohugo.io/installation/) 0.158 or newer.
2. From this folder, run `hugo server`.
3. Open the local address Hugo prints (normally `http://localhost:1313/`).

For a production check, run `hugo --gc --minify`. The generated site is written to `public/`.

## Beta sign-up form

The sign-up form is a MailerLite embedded form shown in the `#beta` section at the bottom of the home page; every "Join the beta" link points there. It is configured in `hugo.toml`:

- `mailerliteAccount` — the account ID from the MailerLite Universal snippet.
- `mailerliteForm` — the embedded form's ID (the `data-form` value in MailerLite's embed code). While this is empty the section shows "Waitlist opening soon" instead.

