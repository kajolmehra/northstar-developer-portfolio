# Architecture

The portfolio uses a Next.js App Router shell with typed React sections and data-driven project pages. A route handler validates contact submissions and can persist them to Neon Postgres when configured. Static content, metadata, and media remain separate from the presentation components so the site can evolve without duplicating page structure.

