# Harada

Static page (GitHub Pages) + Supabase for sync across devices.

## Setup
1. Create a Supabase project. SQL Editor → run `schema.sql`.
2. Authentication → URL Configuration: set Site URL to `https://chrisk447.github.io/harada/` and add it to Redirect URLs.
3. Project Settings → API: copy Project URL and anon key into `config.js`.
4. GitHub repo → Settings → Pages → Deploy from branch `main`, `/ (root)`.
5. Open the site on your phone, sign in with the email link, then Share → Add to Home Screen.
