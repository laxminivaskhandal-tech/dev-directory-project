# DevDirectory

A React and TypeScript developer discovery demo built with Vite. It brings profile discovery, shortlist tools, and project planning into one responsive interface.

## Features

- Search and filter developer profiles by skill and availability.
- View profile details and sample portfolio information.
- Save profiles to a shortlist.
- Draft project briefs and explore a hiring workspace and activity inbox.
- Responsive layouts, clear empty states, and lightweight motion.

## Run locally

1. Install dependencies: `npm install`
2. Start the development server: `npm run dev`
3. Create a production build: `npm run build`

## Supabase setup

The SQL schema is in `supabase/schema.sql`, and `.env.example` shows the required public Vite environment variable names. The current authentication and profile flows are demo UI; real sessions and persistent data require connecting a Supabase client and enabling the database queries. Never expose a Supabase service-role key in browser code.

## Demo data

The developer profiles and activity are sample data for previewing the interface. Connection actions and project briefs are not backed by a production service yet.
