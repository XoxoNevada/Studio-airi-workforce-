# Studio AiRi Workforce Control Center

A live control interface for the Studio AiRi workforce backend.

## Stack
- Static frontend
- Supabase REST data layer
- GitHub source of truth
- Netlify deployment target

## Configuration
Set `window.SUPABASE_ANON_KEY` before loading the app. The frontend must never contain a service-role key.

## Current backend
Supabase project: `dfavqhvgimlmxynsrtwi`

The control center reads projects, employees, tasks, handoffs, QA reviews, and activity. Write operations remain behind protected backend functions.

## Operating principle
DEFINE → PLAN → GOVERN → EXECUTE → MONITOR → CORRECT → COMPOUND

Rachelle remains the final human authority for required review gates.
