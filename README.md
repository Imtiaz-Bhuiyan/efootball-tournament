# eFootball Tournament Manager

A lightweight shared 8-player eFootball tournament manager.

## Features
- Random 2×4 group draw
- 12 round-robin group fixtures
- Automatic points, GD and standings
- Top 2 from each group qualify
- World Cup-style semi-finals, final and third-place match
- Shared cloud persistence with Supabase
- Realtime match updates with polling fallback
- Shareable tournament codes/URLs
- Organizer result reset controls

## Deployment
This is a static single-page app. Deploy the repository with Vercel or any static host. Supabase is already configured in `index.html` for the connected project. Never expose a Supabase service-role key in browser code.

## Database
The Supabase schema and RPC definitions are maintained in the connected Supabase project. `supabase-schema.sql` documents the public tables and required backend functions.
