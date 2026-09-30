# CLAUDE.md

Rules for working on this website project.

## Default editing workflow (local preview)

- For normal website edits, work only on the local files first.
- The default preview method is a local browser preview, not a Vercel preview.
- After making local changes, start or use a local web server and give me the localhost URL to review in my browser.
- Do not create or push a preview branch unless I specifically ask for a Vercel preview or deployment test.
- If I reject the changes or say to undo them, restore the local files back to the clean `main` version and confirm no test changes remain.

## Publishing

- **Never publish or push changes to `main` unless I explicitly approve them.**
- Do not commit, push, merge, or publish anything unless I explicitly approve it.
- Before publishing, summarize exactly what changed.
- Only after I explicitly say something like "publish it live" should you commit and push the approved changes to `main`.
- Before publishing to `main`, summarize the final changes and confirm the version I reviewed is the version that will be published.

## Scope of changes

- Do not make unrelated changes.
- Explain major technical changes before doing them.
- Do not alter forms, analytics, tracking, domain settings, GitHub settings, or Vercel settings unless I specifically ask.
- Keep the website simple and stable.
- Never delete files or run destructive Git commands unless I explicitly approve it.

## Commits

- Use clear commit messages.
