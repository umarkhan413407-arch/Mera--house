# Mera House — Supabase-connected frontend

This package keeps the existing Mera House design and GitHub Pages structure and adds the working browser-side Supabase layer.

## Included
- Supabase Project URL + publishable key configuration.
- Properties loaded from the `properties` table, with demo fallback if the database is unavailable/empty.
- Homepage featured properties from the database.
- Property search/filtering.
- Dynamic property details.
- Supabase email/password Sign In and Sign Up.
- Favorites using the `favorites` table for signed-in users.

## Security
Only the Supabase publishable browser key is included. No secret/service-role key is included.
The frontend cannot bypass Supabase RLS; the existing table policies must permit the requested operations.

## Upload
Extract this ZIP and upload the extracted files to the root of the existing GitHub repository, replacing the old project files. Do not upload the ZIP itself.
