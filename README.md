<div align="center">

# Platinum Crest

**Luxury residential landing page for a G+16 tower in Upper Juhu, Mumbai.**

### [Open the live demo →](https://platinum-corp-demo.vercel.app)

<img src="https://raw.githubusercontent.com/baerozgaarmard/baerozgaarmard/main/assets/platinum.jpg" alt="Platinum Crest hero: A Sanctuary of High-Altitude Living" width="760">

</div>

> An unofficial concept built as a portfolio demo. It is not affiliated with or endorsed by Platinum Corp, so confirm any project detail with the developer.

## What's on the page

- Hero, overview and highlights
- Amenities and floor plans for the 1 and 2 BHK homes
- Video tour
- Location advantages with an interactive Google Map of nearby landmarks
- Comparison, developer track record and buyer-trust sections
- FAQ, contact section and a brochure request form

## Stack

React 19 · TypeScript · Vite · Tailwind CSS 4 · Motion · Google Maps (`@vis.gl/react-google-maps`) · deployed on Vercel

## Run it locally

```bash
npm install
npm run dev
```

The site runs at http://localhost:3000. To show the live map, put a Google Maps key in `.env.local`:

```bash
VITE_GOOGLE_MAPS_PLATFORM_KEY=your_key_here
```

Without a key the map section shows a fallback instead. `npm run build` makes a production build and `npm run lint` type-checks the project.
