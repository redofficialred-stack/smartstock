# SmartStock

Inventory management for small retailers.

## Run locally

Requires Node.js 22.

```sh
npm ci
npm start
```

Open <http://localhost:3000>.

## Deploy on Render

The `render.yaml` Blueprint configures a free Node.js web service. In Render, create a new Blueprint Instance from this repository and apply the Blueprint.

The free service uses an ephemeral filesystem, so SQLite data can be lost when the service restarts, sleeps, or redeploys. Use a paid persistent disk or a managed database for data that must be retained.
