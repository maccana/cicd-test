# CI/CD MkDocs Documentation Demo

This repository demonstrates a minimal continuous integration and deployment (CI/CD) workflow for publishing a documentation site using **MkDocs with the Material theme**. It is designed as a reference implementation for structuring documentation and automating deployment with GitHub Actions.

## Overview

The project includes:

- A documentation site generated with MkDocs Material.
- A content structure for general documentation pages and blog posts.
- Automated deployment to GitHub Pages on every push.

This setup is suitable for technical documentation, internal knowledge bases, and lightweight developer blogs.

## Project Structure

- `docs/` — Root directory for all documentation content.
- `docs/blog/` — Subdirectory containing blog posts written in Markdown.
- `mkdocs.yml` — MkDocs configuration file.
- `.github/workflows/` — GitHub Actions workflows for CI/CD.

## Documentation Content

- General documentation pages are stored directly in the `docs/` directory.
- Blog posts are stored in `docs/blog/` as individual `.md` files.
- Navigation and site structure are configured in `mkdocs.yml`.

## CI/CD Workflow

The repository uses GitHub Actions to automate deployment:

- Trigger: Push to the default branch, such as `main`.
- Build: MkDocs generates the site using the Material theme.
- Deploy: The static site is published to GitHub Pages.

This ensures that updates to the documentation are reflected on the live site automatically.

## Getting Started

1. Install the required dependencies:
   - Python 3.x
   - MkDocs
   - MkDocs Material

2. Run the site locally:
   - `mkdocs serve`

3. Build the site:
   - `mkdocs build`

## Use Cases

- API and developer documentation.
- Internal team knowledge bases.
- Technical blogs alongside documentation.
- CI/CD pipeline demonstrations.

## License

This project is provided for demonstration purposes and can be adapted for your own documentation workflow.
