# CareerIQ MVP

CareerIQ is an interactive AI-career dashboard frontend built with Next.js, React, TypeScript and Tailwind CSS.

## Included MVP flows

- Career-readiness dashboard
- Resume upload and simulated ATS analysis
- Resume-to-job-description matcher
- Skill-based job recommendations
- Personalized dream-career roadmap
- Skill and weekly-goal tracking
- Project/resource recommendations
- Saved reports and user profile

The current analysis results use realistic demo data. Connect the UI to FastAPI, an AI API, Supabase and job-listing APIs to make the backend production-ready.

## Run locally

1. Install Node.js 22 or newer.
2. Open this folder in VS Code.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL shown in the terminal.

## Main files

- `app/page.tsx` — complete interactive CareerIQ UI and flows
- `app/globals.css` — responsive visual system and component styling
- `app/layout.tsx` — metadata, fonts and application shell
