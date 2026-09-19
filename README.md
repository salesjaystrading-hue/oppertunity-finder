# JAYS Project Opportunity Finder PRO

Supabase-backed procurement opportunity finder for JAYS Trading and Business Solution.

## Architecture
- Frontend: static `index.html` hosted by GitHub Pages
- Database/Auth: Supabase project `ufpaxvflwaqesdueqiob`
- Client security: Supabase publishable key + Row Level Security

## Main features
- Excel/TSV project import
- Duplicate detection by Project No + Local Body
- Opportunity scoring and category matching
- Project details and opportunity pipeline
- Staff assignment and follow-up fields
- JAYS product matching
- Import history
- CSV and JSON backup/export

## GitHub Pages
Enable GitHub Pages for the `main` branch using the repository root (`/`).

Never add a Supabase secret/service-role key to this repository. The frontend uses a publishable key and authenticated Supabase access.
