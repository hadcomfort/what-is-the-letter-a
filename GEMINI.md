Title: Researching the Origins of the Letter “A” — Repository Guidance

Scope and goals:
- Trace the development of the letter “A” from Proto-Sinaitic through Phoenician, Greek alpha, Etruscan, and Latin.
- Focus on paleography (shapes and strokes), linguistics (sound values, acrophony), and historical transmission.
- Build a well-cited, accessible knowledge base with small, reviewable contributions.

Output style:
- Use clear headings, short paragraphs, and bullet lists.
- Prefer primary or high-quality secondary sources; include short annotations with each citation.
- When evidence is uncertain or disputed, explicitly state competing hypotheses.
- Keep PRs small and focused.

Citations:
- Use inline citations with links where possible. Examples:
  - (Goldwasser 2011, Israel Museum Journal) link
  - (Sass 1988, An without Catalogue) link
  - (Cross 1967) link
- If paywalled, provide bibliographic details and a stable abstract/summary link.

File and folder conventions:
- docs/ for narrative content (introductions, timelines, overviews)
- sources/ for annotated bibliographies and reading lists
- data/ for small structured data (e.g., JSON or CSV of letterforms over time)
- images/ only if license permits; otherwise link out to museums/collections.
- Each new document starts with: Title, Summary (2–4 sentences), Sources (bulleted), Last updated: YYYY-MM-DD.

Labels (recommended):
- triage-needed, research, bibliography, timeline, data, sources-needed, good-first-task, enhancement, documentation

Typical small tasks (good PRs):
- Add an annotated bibliography entry (sources/…)
- Create or extend a timeline (docs/timeline.md)
- Compare two letterforms across periods (docs/letterforms-…)
- Add a data file mapping letter shapes to dates/sites (data/letterforms.json)
- Improve citations in an existing doc

Command examples for the assistant:
- “@gemini-cli draft an annotated entry for Orly Goldwasser (2011) on Proto-Sinaitic origin with summary and key arguments.”
- “@gemini-cli propose a docs/timeline.md outline linking Proto-Sinaitic → Phoenician → Greek → Etruscan → Latin.”
- “@gemini-cli open a PR adding sources/goldwasser-2011.md and docs/overview.md with a 300-word intro and 5 sources.”

Constraints and quality:
- Avoid unsourced claims. Prefer museum, academic, or epigraphic resources.
- Note artifact IDs, findspots, and dates where relevant.
- Keep images out unless licensing is explicit; otherwise link with credit line.
- Ask for clarification when requirements are vague.

Review checklist (for PR reviewers and the bot):
- Is the scope clear and focused?
- Are sources cited and reputable?
- Can the change be reviewed quickly (small diff, clear structure)?
- Are follow-up tasks identified?
