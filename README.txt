GOLD MEN'S WEAR — Supabase-connected build

1) Open gold-config.js and set:
   - url = your Supabase Project URL
   - publishableKey = your Supabase Publishable key
   Never use a Secret/service_role key here.

2) Upload the whole folder to your web host/GitHub Pages-compatible hosting.
3) Storefront: index.html
4) Admin: admin.html
5) Admin login uses the Supabase Auth user you created. The SQL setup must have created admin_users and the RLS policies.
6) Admin currently manages products and order statuses. Product images are entered as image URLs; Supabase Storage can be added later for direct uploads.
7) Customer orders are saved to orders/order_items and also open WhatsApp.
