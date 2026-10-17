# SUBI TAILOR SHOP

Premium responsive tailoring business website with animated sections, SEO metadata, customer enquiries, optional Supabase database integration, and an admin dashboard.

## Setup
1. Update shop contact details in `config.js`.
2. For online enquiry storage, create a Supabase project and run `supabase/schema.sql` in SQL Editor.
3. Add the Supabase project URL and publishable/anon key to `config.js`. Never expose a service_role key in frontend code.
4. Create an admin user in Supabase Authentication. Add a SELECT policy restricted to that admin UUID; see comments in `supabase/schema.sql`.
5. In GitHub repository Settings → Pages, choose Deploy from a branch, `main`, and `/(root)`.

Files: `index.html`, `styles.css`, `script.js`, `config.js`, `admin.html`, `admin.css`, `admin.js`, `supabase/schema.sql`, `robots.txt`, `sitemap.xml`.
