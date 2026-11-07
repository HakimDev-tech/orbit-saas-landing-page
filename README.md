# Orbit — Workflow workspace

A fictional B2B SaaS concept for small teams that need repeatable operations without losing human oversight.

## Art direction

A dark, almost-black green workspace with a single acid-lime signal color, restrained mono labels, oversized typographic statements, and a realistic product surface as the main visual. No gradient fog, AI-generated abstract hero art, floating glass cards, or fabricated customer proof. The dashboard preview uses meaningful workflow rows, run counts, statuses and step sequences.

## Product story

1. Connect existing tools.
2. Design a visible workflow with owners and conditions.
3. Run it with review points and readable history.

## Stack

Next.js App Router, React, TypeScript and custom CSS. The dashboard filters to workflows needing review and supports selecting a workflow to inspect its steps.

## Run locally

```bash
npm install
npm run dev
```

## Disclosure

Orbit is a fictional product concept. Dashboard values are sample data; no live integrations, accounts, payments or automation executions are connected.

## Deploy on Netlify

1. In Netlify, choose **Add new project → Import an existing project** and select this GitHub repository.
2. Keep the production branch as `main`.
3. The repository includes `netlify.toml`; use Node.js 22 and the Next.js runtime plugin declared there.
4. Trigger the first production deploy, then use the generated `.netlify.app` URL as the canonical site URL before adding sitemap and canonical metadata.

Every push to `main` should trigger a production deploy after the repository is connected. The repository is prepared for Netlify; this README does not imply that a Netlify site has already been created or deployed.
