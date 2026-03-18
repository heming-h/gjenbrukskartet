# Copilot Instructions for gjenbrukskartet

This repository contains static HTML pages and a shared stylesheet.
Prioritize consistency, readability, and simple, maintainable structure.

## Core practices

- Keep edits small and focused on the user request.
- Preserve Norwegian language content and tone in visible text.
- Reuse existing naming patterns and file structure.
- Prefer semantic HTML (`header`, `main`, `section`, `nav`, `footer`) where practical.
- Keep content and presentation separate.
- Avoid introducing new dependencies unless explicitly requested.

## Styling rules (important)

- All styles must go in `gjenbruksmatrisen.css`.
- Do not add `<style>` blocks in HTML files.
- Do not use inline styles (`style="..."`) in HTML.
- If a visual change is needed, create or reuse CSS classes in `gjenbruksmatrisen.css`.
- Keep class names descriptive and consistent with existing naming.

## HTML quality checklist

- Use clear heading hierarchy (`h1` -> `h2` -> `h3`).
- Keep line lengths and formatting readable.
- Ensure links are relative and valid within the repo.
- Add concise comments only when structure is non-obvious.

## Before finishing

- Verify that updated pages still render correctly on desktop and mobile.
- Confirm no new inline or embedded CSS was introduced.
- Keep changes minimal and avoid unrelated refactors.
