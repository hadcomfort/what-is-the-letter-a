Researching the Origins of the Letter “A”

A public, source-conscious exploration of how the letter “A” emerged and evolved—from Proto-Sinaitic signs to Phoenician ‘aleph, Greek alpha, Etruscan adoption, and Latin A. This project collects annotated sources, a small but structured corpus of letterform data, and readable syntheses that connect evidence across time, place, and script traditions.

Goals
- Trace A’s development across major traditions with dates, contexts, and references.
- Compare letterforms (shape, orientation, materials) and phonetic values over time.
- Explain transmission routes and shifts (e.g., acrophony, cultural contact).
- Provide accessible summaries with clear citations and explicit uncertainties.

Key research questions
- What are the strongest lines of evidence for a Proto-Sinaitic origin, and how do they connect to Phoenician usage?
- How and when does ‘aleph become Greek alpha, and what changes in shape and phonetic value occur?
- Through which pathways do Greek forms influence Etruscan and, subsequently, Latin scripts?
- How do writing materials and media (stone, ostraca, papyrus, coins) shape the letter’s form?
- Where do scholars disagree most, and why?

Scope and boundaries
- In scope: Proto-Sinaitic, Phoenician, Greek, Etruscan, Latin; paleography; historical linguistics; epigraphy; archaeology (as needed for context).
- Out of scope: Comprehensive treatment of unrelated scripts; deep philology beyond what’s required for A’s path; exhaustive corpora (we prioritize representative, well-sourced examples).

Methods and outputs
- Annotated bibliography of core scholarship and reference corpora.
- Structured data for representative inscriptions and letterforms (data/letterforms.json).
- Narrative syntheses and focused analyses (e.g., acrophony, transmission routes, letterform evolution).
- Carefully credited visuals or links to external collections when licensing permits.

Repository structure
- docs/ — overviews, timelines, analyses, figures notes
- sources/ — annotated bibliography entries (one file per source)
- data/ — structured datasets (e.g., letterforms.json), optional maps (sites.geojson)
- images/ — only permissively licensed or original diagrams
- GEMINI.md — project-specific assistant instructions
- .github/workflows/ — automation (reviews, triage, assistant)

Roadmap (high level)
- Phase 1: Define scope and questions (overview, boundaries)
- Phase 2: Build core bibliography (20–30 annotated sources)
- Phase 3: Seed dataset (50–100 entries across traditions)
- Phase 4: Timeline and geography (timeline.md; optional sites map)
- Phase 5: Comparative analyses (letterform evolution, acrophony, routes)
- Phase 6: Visuals (original diagrams; licensed assets)
- Phase 7: Publication pass (findings.md; optional GitHub Pages)
- Phase 8: Feedback loop (expert/community review)
- Phase 9: v1.0 release; ongoing maintenance

How to contribute
- Open an issue with a clear title, scope, and references. Use labels: research, bibliography, timeline, data, sources-needed, documentation.
- Keep PRs small and focused. Every new doc should begin with: Title, Summary (2–4 sentences), Sources (bulleted), Last updated: YYYY‑MM‑DD.
- Cite sources inline with enough detail to find them again (author, year, venue, pages; link if open-access).
- Use @gemini-cli in issues/PRs to draft entries, propose outlines, or open small PRs on your behalf.

Data and licensing
- Only include images you created or those with explicit, permissive licenses; otherwise link out with proper credit.
- Datasets should cite their provenance (museum ID, corpus number like KAI/CIS/EDH/PHI when applicable).
- Include a LICENSE file for text and data. If unsure, MIT or CC BY 4.0 are common choices for open research content.

Selected starting references (non-exhaustive)
- Orly Goldwasser — “How the Alphabet Was Born from Hieroglyphs” (2011)
- Benjamin Sass — The Genesis of the Alphabet and its Development in the Second Millennium B.C. (1988)
- Joseph Naveh — Early History of the Alphabet (2nd ed., 1987/1997)
- Christopher A. Rollston — Writing and Literacy in the World of Ancient Israel (2010)
- Peter T. Daniels & William Bright (eds.) — The World’s Writing Systems (1996)
- Roger D. Woodard — Greek Writing from Knossos to Homer (1997)

Status
- Active; early phases. See issues and milestones for current tasks.

Acknowledgments
- Built openly with community input. This repo uses GitHub Actions and the Gemini CLI to assist with triage, reviews, and small task execution.

Citing this project
- Consider adding a CITATION.cff for easy citation. Until then, cite the repository URL and commit/tag used.

Next steps you can take right now
- Open an issue: “Seed bibliography: 10 core sources” and ask @gemini-cli to draft annotated entries for two of them.
- Create data/data-dictionary.md and data/letterforms.json with the schema you prefer; then ask @gemini-cli to propose 5 starter rows.
- Start docs/timeline.md with 8–12 milestone entries; ask @gemini-cli to refine and source each entry.

If you want, I can also draft ISSUE_TEMPLATEs (Research Task, Bibliography Entry) and a data schema starter for data/letterforms.json.
