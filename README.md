# SharePoint Skills

A curated library of AI skills for the latest AI features in Microsoft 365 SharePoint.

> **Status:** Active — new content added regularly.

---

## What's Inside

| Folder | Purpose |
|---|---|
| [`Skills/`](./Skills/) | AI skills — each skill in its own folder, ready to install into a SharePoint agent |

---

## Prerequisites

- Microsoft 365 tenant with **Copilot license**
- SharePoint contributor permissions (to add/upload a skill, but only reader needed to consume)

---

## Contributing

Contributions and corrections are welcome!

1. Fork the repo and create a branch: `git checkout -b skill/your-skill-name`
2. Add your skill folder under `Skills/` (e.g., `Skills/my-skill/`)
3. Include the following files in your skill folder:
   - `SKILL.md` — the skill instructions with `name` and `description` frontmatter (folder name must match `name` exactly)
   - `README.md` — description of what the skill does, what you get, and a contribution table with your name, GitHub handle, and publish date
   - `assets/sample.json` — metadata for the PnP community samples gallery
   - `assets/preview.png` — a screenshot showing the skill's output (used in the samples gallery)
4. Open a pull request with a short description of what the skill does

---

## License

[MIT](./LICENSE) © 2026 [pnp](https://github.com/pnp)

---

## Disclaimer

These skills are provided as-is for learning and experimentation. They are not official Microsoft documentation. Always verify against the latest [Microsoft Learn](https://learn.microsoft.com) docs before deploying to production.
