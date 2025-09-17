# Amateur Trail Runners Association (ATRA)

A simple, fast website for the Amateur Trail Runners Association. Built with Next.js, React, and Tailwind CSS.

## Quick Start

Prerequisites:
- Node.js 18+ (recommend 20+)
- npm

Install dependencies:

    npm install

Run the development server:

    npm run dev

Build for production:

    npm run build

Start the production server (after build):

    npm run start

Lint the project:

    npm run lint

## Project Structure

- `src/app/`
  - `layout.tsx` — Root layout and site metadata
  - `page.tsx` — Home page (ATRA content)
  - `globals.css` — Global styles (Tailwind CSS)
- `public/` — Static assets (served at the site root)

## Customization

- Update site title/description in `src/app/layout.tsx`.
- Edit the home page content in `src/app/page.tsx`.
- Add new routes by creating folders and `page.tsx` files under `src/app` (for example, `src/app/about/page.tsx`).

## Scripts

- `dev` — Start the dev server with Turbopack
- `build` — Create an optimized production build
- `start` — Run the production server
- `lint` — Run ESLint

## Deployment

- Build the app with `npm run build`, then run `npm run start` on your hosting platform.
- Ensure the environment uses Node.js 18+ and serves the app on your desired port (default: 3000).

## License

Proprietary — all rights reserved unless otherwise noted.