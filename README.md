# Moche — Supabase-connected build

This build connects the Moche frontend to the Supabase project configured in the app.

## Supabase setup
In Supabase, go to Authentication → URL Configuration and add:
- Site URL: https://moche2026.github.io/Moche/
- Redirect URL: https://moche2026.github.io/Moche/

The database tables and RLS policies should already be created from the Moche SQL migration.

## Included
- Supabase email magic-link authentication
- Real profiles
- Real jobs
- Real offers
- Customer/worker profiles and ratings
- Offer review/confirmation flow
- Hiring and offer status
- Other job types
- No browser localStorage for marketplace data
