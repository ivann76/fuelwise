# Fuelwise

Open index.html in your browser, or open the folder in VS Code and use Live Server. No installation or backend is required.

Files:
- index.html: page layout and form
- style.css: responsive design
- app.js: records, charts, local saving, backup import/export

Records are saved in browser localStorage, separately for each browser and website address. Export backups before clearing browser data. Google Fonts requires an internet connection; fallback fonts work offline.

For comparison, enter litres filled, then finish the tank with distance driven. Efficiency = total completed kilometres / total completed litres for each brand. Use similar starting and ending fuel levels.

Mobile update: sticky navigation, stacked history cards, full-width action button, one-column scrollable forms, larger touch targets, decimal keyboards, and an SVG petrol pump logo/favicon.

Phone navigation: Overview and Fuel history are fixed to the bottom, with active indicators and safe-area padding.

Mobile fill-up action: tap the central plus button between Overview and Fuel history.

Design refresh (iPhone 16 Pro Max): safe-area aware layout for the Dynamic Island and home bar, floating bottom navigation with a raised "+" button, a hero distance card, the fill-up form as a slide-up bottom sheet, 16px inputs (no iOS zoom), and Add-to-Home-Screen support (apple-touch-icon.png + manifest.webmanifest).

Monthly totals: "Fuel logged" and "Fuel spend" follow the month picker above the stats. It defaults to the current month, so a new month starts at zero automatically. Older months are never deleted: pick any month (or All time) to see its totals.

Home Screen app: host the folder on any https site (GitHub Pages, Netlify, Cloudflare Pages), open it in Safari on iPhone, then Share > Add to Home Screen. It opens full-screen with the Fuelwise icon. Note: the Home Screen app has its own storage, separate from Safari, so use Export backup in Safari and Import in the app once.
