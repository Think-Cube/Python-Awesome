# Contributing to Awesome Python

Thank you for your interest in contributing! This document describes how to add or update entries in this curated list.

## Quality Standards

This list follows the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md). All submissions must meet these criteria:

- **Actively maintained** — last commit within 12 months or is a stable, widely-used project.
- **Well documented** — has a README, docs site, or clear API reference.
- **Widely used or noteworthy** — significant GitHub stars, PyPI downloads, or strong niche use case.
- **Production ready** — not a toy project or early alpha (unless in an `Experimental` section).
- **Python-focused** — directly relevant to Python development.

## How to Add an Entry

1. **Fork** this repository.
2. **Create a branch**: `git checkout -b add/library-name`
3. **Edit `README.md`**:
   - Add the entry to the most appropriate category, in alphabetical order within the category.
   - Use this format:
     ```markdown
     - [Library Name](https://link-to-docs-or-github.com/) - One sentence description starting with a capital letter, ending with a period.
     ```
   - Keep descriptions concise (under 120 characters).
   - Link to official documentation, not GitHub, when a docs site exists.
4. **Run validation locally** (see below).
5. **Open a Pull Request** using the PR template.

## PR Checklist

- [ ] Entry is in alphabetical order within its section.
- [ ] Description starts with a capital letter and ends with a period.
- [ ] Link goes to official docs or GitHub (not a blog post or mirror).
- [ ] No duplicate entry exists.
- [ ] The library is not deprecated or abandoned.
- [ ] PR title follows the format: `Add: LibraryName` or `Update: LibraryName` or `Remove: LibraryName`.

## Removing an Entry

Open an issue using the **Remove Resource** template explaining why the entry should be removed (abandoned, deprecated, security vulnerability, etc.).

## Local Validation

Install dependencies and run the validation script:

```bash
pip install -r scripts/requirements.txt
python scripts/validate.py
```

This checks:
- All URLs return HTTP 200 (or redirect to a valid page).
- Descriptions match the required format.
- No duplicate links.

## Categories

If you believe a new category is needed:

- It must contain at least **5 entries** at the time of creation.
- Open an issue first to discuss before submitting a PR.
- Add the category to the **Contents** section in alphabetical order.

## Code of Conduct

By contributing, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).
