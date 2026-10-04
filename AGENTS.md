# AGENTS.md

## Project

This is a Hugo-based Software Architect portfolio site.

## Content Structure

- content/about.md
- content/experience.md
- content/expertise.md
- content/projects/
- content/technologies/
- content/publications.md

## Hugo

Required local Hugo version:

v0.154.5+extended

Before finishing any change, always run:

hugo --minify

Do not consider the task complete if the Hugo build fails.

## Editing Rules

Do not directly modify generated files under:

public/

Edit only source files such as:

- content/
- layouts/
- assets/
- static/
- hugo configuration

## Deployment

Production deployment:

GitHub Pages via GitHub Actions.

Production domain:

skills.xsim2026.shop

CNAME:

static/CNAME

Workflow:

.github/workflows/pages.yml

## Git Workflow

Before editing:

git status
git pull --ff-only

After editing:

git diff
hugo --minify

Do not push automatically unless explicitly requested.

## Theme

Theme:

themes/triple-hyde

Avoid modifying theme files directly unless necessary.

Prefer Hugo overrides under the project-level layouts/ directory.

## Compatibility

The project has previously encountered Hugo-version compatibility issues involving:

themes/triple-hyde/layouts/about/single.html

When modifying templates, preserve compatibility with Hugo v0.154.5+extended.
