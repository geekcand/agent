Agent Lite + Admin Analytics

FILES
- index.html : original Agent Lite with anonymous usage tracking added.
- admin.html : protected admin dashboard.

BACKEND
Connected to the existing Supabase project: My tool.
Database/RPC functions are already created and protected with RLS.

ADMIN LOGIN
Username: admin
Password: YTBBnCjahgcoxOFU10

DEPLOYMENT
Upload index.html and admin.html to the same GitHub Pages repository.
Normal users open index.html with no login.
Admin opens /admin.html.

PRIVACY
The analytics stores an anonymous random device id, session timestamps, current page, browser name, platform, screen size and mobile/desktop flag. It does not store employee name, email, phone number, canned-text content, searches, or clipboard content.
