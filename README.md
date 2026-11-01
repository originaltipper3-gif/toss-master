# Toss Master — Official Telegram Channel

A one-page landing page for the Toss Master Telegram channel. Visitors see the channel card with a 15-second circular countdown, then get redirected to the Telegram invite link automatically. They can also tap **JOIN NOW TELEGRAM** to go right away.

## Technologies

- Plain HTML, CSS, and vanilla JavaScript in a single `index.html` with no build step
- Hosted on Netlify, which serves the project root (see `netlify.toml`)

## Running locally

Open `index.html` in a browser, or run `netlify dev` to use the Netlify CLI.

## Changing the invite link

The Telegram URL appears twice in `index.html`: in the button's `href` and in `targetUrl` in the script. Update both.
