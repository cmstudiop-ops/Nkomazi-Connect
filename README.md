# Nkomazi Connect

Responsive community discovery and publishing platform for Nkomazi, South Africa.

## Features
- Mobile-friendly homepage and navigation
- Business, jobs, events, education, updates, explore and community categories
- Search and area filtering
- Supabase email/password registration and login
- Authenticated public posts, likes, reports and real-time post updates
- PostgreSQL Row Level Security policies

## Backend
Supabase project: `akzcffayklqxdbeddtda` (Nkomazi Connect). Frontend uses the public publishable API key only. Never commit service-role keys.

## Deployment
Publish `index.html` from the repository root using GitHub Pages: Settings > Pages > Deploy from a branch > main / (root). Confirm your Supabase Auth Site URL and redirect allowlist include the published site.

## Current scope
This is an initial working foundation, not a complete production-ready platform. It does not yet provide image uploads, dedicated business profiles, job application flows, payments, advanced moderation dashboards, or comprehensive abuse prevention. Before public launch add rate limits, content moderation, privacy policy, terms, and security testing.
