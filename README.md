# ED AI — Next Version

This is a mobile-friendly static prototype.

## Files
- `index.html`: app interface and local image/video preview.
- `README.md`: setup notes.

## Current limits
This version does not generate AI videos; it prepares a request in the browser. A real integration needs a compatible provider/API and a secure backend to keep credentials private. Free demos may have queues, quotas, downtime, and terms that limit reuse. Never put secret API tokens in `index.html`.

## Free hosting
Static HTML can be hosted on a free static-site plan subject to that provider's current terms. Upload `index.html` as the entry page.

## Later integration
1. Choose a provider whose API terms permit use in your app.
2. Confirm free quota and authentication requirements.
3. Add a server endpoint and store any token as a secret environment variable.
4. Call the provider from that endpoint and return the generated video URL.
5. Add file-size/type checks, rate limits, and a privacy notice before public launch.

No ad system or account system is implemented.
