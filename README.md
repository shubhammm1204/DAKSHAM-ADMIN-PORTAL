# DARKSHAM Admin Portal (frontend prototype)

## Run
Open `index.html` in a modern browser, or use VS Code Live Server.

## Included
- Responsive sidebar and dashboard
- Dashboard statistics derived from local data
- Event, stall, announcement, schedule, sponsor and media CRUD
- Search and status filters
- Fest settings with preview
- Activity log
- Browser `localStorage` persistence

## Important
This is a frontend-only prototype. Data is stored in the current browser using localStorage. It is not a secure multi-user system and does not yet sync with the public DARKSHAM website. For production, connect the UI to a backend API and database, add authentication/authorization, and use cloud media storage. Never store admin passwords or secrets in frontend JavaScript.
