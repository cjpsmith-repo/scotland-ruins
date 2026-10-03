# Scotland Ruins Gazetteer

Ruined castles, abbeys, cathedrals, kirks and mansions across Scotland, ranked for a small wedding ceremony.
Single self-contained page: `index.html`. Photos are from Wikimedia Commons and credited on the page.
The shortlist saves to a Google Sheet through an Apps Script web app.

Live at https://scotland-ruins-gazetteer.netlify.app

The "Distance by car" filter looks places up in a built-in list of Scottish towns (plus the towns named in the data), then falls back to Nominatim geocoding. Road distances and drive times come from the public OSRM demo server, fetched in the browser and cached per origin; if routing is unreachable the page shows a clearly labelled straight-line estimate instead.
