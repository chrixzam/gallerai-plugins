# Gallerai for ChatGPT and Codex

Use your Gallerai gallery from ChatGPT and Codex: ask about your inventory, artists, collectors and deals, and let it log calls and set follow-ups.

You need a Gallerai account. Nothing here works without signing in to Gallerai: the plugin only points ChatGPT at Gallerai's server, and every request is limited to the gallery and permissions you approve.

## Add it to ChatGPT

1. In ChatGPT, open **Plugins** → **Add** → **Plugin marketplace**.
2. Paste `chrixzam/gallerai-plugins` in **Source** and click **Add marketplace**.
3. Install **Gallerai**, then sign in to Gallerai and approve.

Workspace admins (ChatGPT Business / Enterprise) can add it for everyone: Admin Console → Plugins → Add → Import marketplace.

## Add it to Codex

```bash
codex plugin marketplace add chrixzam/gallerai-plugins
codex plugin add gallerai@gallerai
```

## Help

Setup steps are also in Gallerai under Settings → Integrations → AI tools → ChatGPT. Questions: https://gallerai.space/developers
