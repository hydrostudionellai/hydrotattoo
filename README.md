# Hydro Tattoo Nellai — React website

Responsive promotional website built with React + Vite. Includes the supplied logo, two tattoo work photos, artist-at-work photo and WhatsApp QR image.

## Run locally (Windows / macOS / Linux)
1. Install Node.js 22 LTS or newer.
2. Extract this ZIP and open the `hydro-tattoo-react` folder in VS Code.
3. Open a terminal in that folder:

```sh
npm install
npm run dev
```

Open the localhost URL shown in the terminal (usually http://localhost:5173).

To specify a port: `npm run dev -- --port 5174`

## Production
```sh
npm run build
npm run preview
```
Upload the generated `dist` folder to a static host such as Netlify or Vercel (build command: `npm run build`, output: `dist`).

## Features
- Responsive mobile navigation
- Tattoo gallery with accessible native-dialog image viewer
- Services, artists, studio details and FAQ
- WhatsApp enquiry form with browser validation and prefilled message
- Click-to-call, Instagram, Google Maps directions and WhatsApp QR
- Reduced-motion support

The form opens WhatsApp; the visitor must send the message there. It does not save enquiries, upload images, send automatically or confirm appointments. Visitors can attach reference images in WhatsApp. Pricing and opening hours are not invented.

## Edit
- Content, phone, address, artists and links: `src/main.jsx`
- Colours, layout and responsive styles: `src/styles.css`
- Images: `public/images`
- Page title and description: `index.html`

Google Fonts are optional remote fonts; the website uses system fallbacks when offline. All supplied photographs are bundled locally. No API key or backend is required. The supplied WhatsApp QR image is included unchanged; chat buttons use the provided phone number.
