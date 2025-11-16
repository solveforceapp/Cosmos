# Site Layout Guidelines (Canonical Template)

Use this minimal per-page footer/contact block at the end of every Markdown file to achieve consistent layout across the site. Copy the "Site footer" block as-is to the bottom of each content page.

Site header (per-page top-of-file):
- Keep page title as the first top-level header (# Title)
- Optional: one short description paragraph below the title

Site content:
- Keep sections small and focused (one concept per file)
- Use relative links to other pages using the existing lowercase, hyphen-separated names

Site footer (place at the bottom of every page):
```
---
Contact: Cosmos Knowledge Base — SolveForce  
Email: contact@solveforce.com  
For corrections or suggestions, please open an issue in the repository.
---
```

Notes:
- Replace contact@solveforce.com with your official contact address if different.
- If you prefer a single central contact page, link to content/includes/contact.md from each page with a short footer line, e.g., "See <a>Contact</a>" — adjust relative path based on folder depth.
- For glossary entries (in content/glossary/), place the footer after the main definition content.
