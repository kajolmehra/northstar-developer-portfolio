![Northstar Developer Portfolio](assets/cover.svg)

# Northstar Developer Portfolio

> A polished personal-brand and lead-capture experience for a full-stack product engineer.

[![Case study](https://img.shields.io/badge/case%20study-private%20delivery-6658DC)](SECURITY.md)
[![Next.js](https://img.shields.io/badge/Next.js-15-000000?logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-149ECA?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

## Overview

A responsive developer portfolio designed to present complex product work clearly, explain services, showcase selected case studies, and capture inbound project enquiries. The implementation uses the Next.js App Router with reusable sections, project detail routes, theme switching, SEO metadata, and an API-backed contact form.

## My contribution

- Information architecture for services, process, work, and contact conversion
- Reusable React sections and accessible UI primitives
- Dynamic project detail pages with image galleries and technology summaries
- Dark/light theme support and responsive layouts
- Contact API with optional Neon Postgres persistence
- SEO metadata, canonical URLs, sitemap-ready configuration, and deployment setup

## Skills demonstrated

| Area | Applied |
| --- | --- |
| Next.js | App Router pages, layouts, metadata, route handlers, and production deployment conventions |
| React / TypeScript | Typed content models, reusable sections, composable UI, and predictable component contracts |
| Tailwind CSS | Responsive design system, theme tokens, spacing rhythm, and polished interaction states |
| Data | Neon serverless Postgres integration for contact submissions with environment-based configuration |
| UX | Case-study storytelling, service positioning, project filtering, conversion-focused contact flow |
| Quality | Production build scripts, type checking, responsive behavior, and privacy-safe content management |

## Representative flow

```mermaid
flowchart LR
    Visitor[Portfolio visitor] --> Work[Browse selected work]
    Work --> Detail[Open project case study]
    Detail --> Contact[Send project enquiry]
    Contact --> Validate[Validate request]
    Validate --> Store[(Optional Neon Postgres)]
    Validate --> Notify[Confirmation response]
```

## Technical stack

Next.js 15 · React 19 · TypeScript · Tailwind CSS 4 · App Router · Lucide icons · Neon Postgres · Vercel-ready deployment.

## Privacy note

This is a portfolio presentation, not a copy of the private website. Names, URLs, contact details, project content, and media are anonymized. See [architecture](docs/ARCHITECTURE.md), [user flow](docs/USER-FLOWS.md), [security policy](SECURITY.md), and [screenshot guide](docs/SCREENSHOT-GUIDE.md).
"# northstar-developer-portfolio" 
