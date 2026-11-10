# Pin the Door · Delhivery

A one-page case study by Modit Joshi. It covers two problems in the **Delhivery B2C app**, the app individuals use to send parcels. The business app and Delhivery One don't have these problems.

1. **Multi-box shipments.** One shipment of several boxes gets split into separate orders that arrive on different days.
2. **Location.** A typed address with no pin on the door sends riders on detours and repeat calls.

For each problem the page shows the fix side by side with today's flow, app screens (before and after), how the pin is validated, integrations, edge cases, cost and payback, metrics, and a short feedback form.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole site in one file. HTML, CSS and JS are inline, with no build step. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |

## Feedback form

Answers go to a Google Sheet through a Google Apps Script web app. Its URL is in `index.html`; search for `script.google.com`. The page sends each submission in the background and shows a thank-you in place.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Hosting

The site is served by GitHub Pages from the `main` branch root.
