# Webcraft Kids — deployment

This repository is intended for the Webcraft Kids static site.

## Cloudflare Pages
1. In Cloudflare dashboard, open Workers & Pages and create a Pages project.
2. Connect this GitHub repository when the website files have been committed.
3. Set production branch to `main`, build command blank, output directory `/`.
4. After Cloudflare provides a `*.pages.dev` URL, configure that URL in Supabase Authentication > URL Configuration as Site URL and an allowed redirect URL.

## Important
The full website `index.html` and illustrations have not yet been committed. Do not deploy this repository as a finished website until those assets are present.

Do not commit Supabase service-role keys, premium activation codes or other secrets.
