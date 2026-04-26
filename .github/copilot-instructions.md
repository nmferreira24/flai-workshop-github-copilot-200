# Copilot Instructions

## Project Overview

This is an educational assignment portal for **Mergington High School — Computer Science** course. It is a static website that lets students browse, view, and download coding assignments.

## Project Structure

- `index.html` — Main portal page; content is driven by `config.json`
- `config.json` — Source of truth for course metadata and assignment list
- `assignments/<id>/` — One folder per assignment, each containing:
  - `README.md` — Assignment instructions (follows `templates/assignment-template.md`)
  - `starter-code.py` — Python starter file for the student
- `assets/css/styles.css` — Shared styles; keep consistent across all pages
- `assets/js/script.js` — Vanilla JS (`AssignmentPortal` class) that reads `config.json`
- `templates/assignment-template.md` — Template for new assignment README files

## Coding Guidelines

- **Frontend**: Plain HTML, CSS, and vanilla JavaScript — no frameworks
- **Python assignments**: Target beginner-to-intermediate Python; assignments focus on fundamentals (variables, loops, conditionals, classes, data analysis)
- **Naming**: File and folder names must be lowercase, hyphen-separated, and descriptive
- **Styling**: Do not introduce new CSS patterns; reuse existing classes from `styles.css`

## Adding a New Assignment

1. Create `assignments/<id>/` with `README.md` and `starter-code.py`
2. Write `README.md` using `templates/assignment-template.md` as the base — preserve the emoji headers and section structure
3. Register the assignment in `config.json` under the `assignments` array with `id`, `title`, `description`, `path`, `dueDate`, and `attachments`

## Content Standards

- **Learning-focused**: Every assignment must have a clear objective and explicit, measurable requirements
- **Student-friendly**: Use clear, encouraging language; include example inputs/outputs in task descriptions
- **Difficulty labeling**: Match task complexity to the course level (intro Computer Science)