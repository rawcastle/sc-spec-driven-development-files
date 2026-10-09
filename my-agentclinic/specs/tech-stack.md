# AgentClinic Tech Stack

## Direction

Use TypeScript across the application. Adopt **Next.js with the App Router** as the full-stack framework, keeping the agent and staff dashboards and their server-side workflows in one application. This is a recommendation for the project to adopt; the current repository is only a minimal TypeScript starter and does not yet contain an application framework.

## Principles

- Keep TypeScript strict and validate untrusted input at application boundaries.
- Use server-side code for appointment and staff workflows; do not rely on browser state as the source of truth.
- Build accessible, responsive interfaces that work in current modern browsers.
- Keep domain rules independent of presentation so care and booking workflows can be tested directly.
- Add persistence when the first end-to-end workflow needs it; use SQLite for durable clinic data.
- Choose supporting libraries when a concrete phase needs them, and keep the dependency set focused.

## Framework Choice

Next.js is the recommended framework because it supports a TypeScript web interface and server-side application code in a single, widely used project structure. Revisit this choice only if the product gains requirements that warrant a separate backend service.