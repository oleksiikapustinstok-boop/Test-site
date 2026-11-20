# Website Demo Hub

Starter Cloudflare Worker for English-language small-business website previews.

## Deployment

Connect this GitHub repository to the existing Cloudflare Worker named `beta-page`. Set the deploy command to `npm run deploy` and the build command to `npm install` if prompted. Do not publish credentials in this repository.

## Current limitations

Preview records are hardcoded in `src/index.js`. The 90-day expiry is checked on requests, not a scheduled deletion. This is an initial demo, not yet a CRM, authenticated editor, payment integration, or automated outreach system.
