# Opinly Blog

Live site: https://<your-project>.vercel.app

## Running it

    npm install
    npm run dev      # http://localhost:3000
    npm test

Requires Node 20+. Environment variables: (to be filled in once the SDK is set up)

## Technical decisions and trade-offs

- **Next.js on Vercel:** fastest path to a public URL, and Opinly's own blog runs on the same SDK.
- **Vitest:** lightweight test runner. Needed `@types/node` bumped to v24 to resolve a peer dependency conflict with the Next.js template's default.

## What I'd do with more time

-

## SDK notes and issues

-

## How I used AI

- Used Claude to plan the exercise, scaffold the project and debug setup errors (dependency conflict, package.json syntax).
- Reviewed and ran every command myself.