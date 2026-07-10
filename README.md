# Yuxia Ding's Personal Homepage

This repository contains the source code for my academic personal homepage:

<https://YuxiaDing.github.io/>

The site presents my academic profile, education, experience, selected projects, skills, awards, and CV.

## Repository Structure

- `content/`: Markdown content for the homepage, profile, projects, blog posts, and other pages.
- `content/authors/admin/`: Main profile and resume data.
- `content/projects/`: Selected project pages.
- `static/uploads/`: Static files such as the resume PDF.
- `config/_default/`: Site configuration, menus, language settings, and theme parameters.
- `assets/`: Site assets and custom media.
- `.github/workflows/`: GitHub Pages deployment workflow.

## Local Preview

Install Hugo Extended and Node.js, then install the front-end dependencies:

```bash
pnpm install
hugo server --disableFastRender
```

The local site is usually available at:

```text
http://localhost:1313/
```

## Build

To generate the static site:

```bash
hugo --minify
```

The generated files are written to `public/`.

## Deployment

The site is deployed to GitHub Pages through the workflow in `.github/workflows/deploy.yml`.
