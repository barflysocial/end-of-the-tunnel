# The End of the Tunnel

Mobile-friendly live hosted murder mystery game for The Tunnel in Baton Rouge. Built from the live-hosted sponsor-popup template and rethemed with new truth packs, title screen, host labels, check-in flow, RSVP/access-code support, and automated sponsor popups.

## Run locally

```bash
npm install
npm start
```

Open:

```text
http://localhost:3000/host/
http://localhost:3000/player/
http://localhost:3000/checkin/
```

## Render settings

```text
Runtime: Node
Build Command: npm install
Start Command: npm start
NODE_VERSION: 20.18.1
```

## Notes

- Do not upload `node_modules` to GitHub.
- The app uses PostgreSQL when `DATABASE_URL` exists. Without it, local sessions save to `./data/sessions.json`.
- Truth packs are in `/truth-packs/`.
