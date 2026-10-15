# RHO-12 // The Grace — Starter Website

A static, in-universe SCP:RP faction archive built with HTML, CSS, and vanilla JavaScript.

## Files

- `index.html` — page structure and starter content
- `styles.css` — dark classified-database visual theme and responsive layout
- `script.js` — searchable/filterable archive and document pop-ups

The sample archive records are stored near the top of `script.js` in the `records` array. Copy an existing object and change its `id`, `category`, `title`, `status`, `summary`, and `body`.

Supported categories: `Lore`, `Operations`, `Equipment`, `Resources`, and `Personnel`.

Keep record IDs unique. The document pop-up uses `textContent` for record fields, which is safer than inserting arbitrary HTML from user-editable text.

## Public website safety

- Do not put passwords, API keys, private Discord invite tokens, or personal information in these files.
- Everything committed to a public repository should be treated as public.
- A static GitHub Pages site does not provide private member accounts or secure server-side access controls.
- Mark the project as fan-made and in-universe; do not imply official affiliation with the SCP Foundation Wiki or Roblox.

Do not put a service-role secret or password in website JavaScript. GitHub Pages can host the front end, but owner-only editing requires the external authentication/database setup.
