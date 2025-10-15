# Contributing

Thanks for your interest in contributing to the Quantum × Machine Learning Hub!

## How to contribute

1. **Open an Issue** describing:
   - what you want to add/fix, and
   - why it belongs here (quality, relevance, recency).
2. **Fork** and create a feature branch:
   ```
   git checkout -b feat/topic-short-name
   ```
3. **Make changes** following the structure and style below.
4. **Run checks** (link validity, markdown lint).
5. **Open a Pull Request** using the template in `.github/pull_request_template.md`.

## Style & Structure

- Keep summaries **concise** (2–4 sentences) with **tags**: `[theory] [survey] [kernel] [VQA] [hardware] [NISQ] [benchmark]`.
- Prefer **official docs/papers** and **archival links**.
- When adding a paper:
  - Put BibTeX in a `.bib` file (same folder) and reference it from the local `README.md`.
  - Add 2–3 bullet takeaways and a link to code (if available).
- When adding notebooks:
  - Put them in `notebooks/<topic>/` with a **top cell** describing goals, environment, and runtime.
  - Include a `requirements.txt` in the folder if additional deps are needed.

## Quality Bar

- Avoid link rot; prefer canonical sources.
- Avoid marketing-heavy or non-substantive posts.
- Prefer resources with **reproducible code** or **clear theory**.

## Checks before PR

- [ ] All links resolve
- [ ] No large binaries in git (use LFS if needed)
- [ ] Folders and filenames are kebab-case
- [ ] Added yourself to `contributors` in the PR

Thank you!
