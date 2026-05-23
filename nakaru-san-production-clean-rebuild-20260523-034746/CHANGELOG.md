# Changelog

## 2026-05-23 - Production rebuild

- Rebuilt Nakaru-San as a clean Vite + React app.
- Added a polished anime/gaming social platform layout.
- Added profile owner/edit behavior so Save Profile only appears while editing.
- Added profile photo and banner upload controls.
- Added YouTube link posting with embed conversion and feed rendering.
- Added public chatroom pages and room-specific messages.
- Added private room, inbox, DM conversation, GoLive, video preview, and call preview screens.
- Added Supabase Auth, database, storage, and realtime-ready wiring.
- Added `supabase/schema.sql` with RLS policies.
- Added Render, Vercel, and local deployment instructions.
- Removed dependency on old backend paths and stale root/public static files by isolating the new production app in this folder.
