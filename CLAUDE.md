# CLAUDE.md - SafeSky Digital Agency

## Project Identity
- **Name:** SafeSky Digital Agency
- **Description:** Premium interactive agency website
- **Repository:** Odadsonjoseph/safesky
- **Branch:** main
- **Supabase Ref:** N/A
- **Vercel Project:** safesky
- **Tech Stack:** Next.js, TypeScript, Tailwind CSS, Framer Motion, Vercel

## CRITICAL: Project Isolation
You are working on **SafeSky Digital Agency** and ONLY SafeSky Digital Agency.
- Do NOT reference code, configs, or data from other projects
- Do NOT deploy to any other Vercel project
- Do NOT modify any other Supabase instance
- Verify: `git remote -v` must show `Odadsonjoseph/safesky`

## Standards
- Follow the company AGENTS.md universal operating protocol
- Use the quality-gate skill before every commit
- Use the git-workflow skill for all branching and PRs
- Use the security-hardening skill before every deployment
- All code must pass TypeScript strict mode
- All Supabase tables must have RLS enabled

## Environment
- Local dev: `npm run dev` or `pnpm dev`
- Build: `npm run build`
- Deploy: `vercel --prod --token $VERCEL_TOKEN`
- Supabase: `supabase` CLI with `$SUPABASE_ACCESS_TOKEN`
