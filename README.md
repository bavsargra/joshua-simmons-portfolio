# Cozy Portfolio Site

Static Astro portfolio for biography, resume, projects, tutoring, and contact.

## Edit Content

Most copy lives in `src/data/site.json`. Update that file to change your name, bio, resume entries, projects, tutoring subjects, links, and contact email.

Images can be added under `public/assets/` and referenced from the JSON content later.

## Commands

```bash
npm install
npm run dev
npm run build
```

This workspace uses current Astro, which requires Node 22+. The npm scripts call the Codex-bundled Node runtime directly on this machine, so they work even if your default terminal Node is older.
