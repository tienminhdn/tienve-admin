# Tiền Về · Admin console

Static admin page (withdrawal payouts). Built from the private `cashback-app` repo (`admin/`).
`config.js` only holds the Supabase project URL and the **public anon key**; every admin action
requires an admin login and is authorised server-side (Edge Function `admin`, `profiles.role = 'admin'`).
