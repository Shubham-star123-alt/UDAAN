# UDAAN v5 QA checks

- JavaScript syntax: `node --check script.js` passes.
- Scholarship dataset: 19 source-linked records, including 7 school-stage scholarship records.
- School-stage filter: Primary (1–5), Secondary (6–10), and School (1–10) filters are wired to the scholarship renderer.
- YouTube learning: class selectors exist for Classes 1–12; school stage filtering separates 1–10 from 11–12; verified direct videos are included alongside live verified-channel class/subject hubs.
- Senior secondary: subject hubs cover Physics, Chemistry, Mathematics, Biology, English, Computer Science, Accountancy, Economics, Business Studies, History, Political Science and Geography for Classes 11 and 12.
- Theme: persistent light/dark mode stored in localStorage; dark theme has dedicated section/card/modal/map overrides.
- Profile: no profile-builder controls are present; saved items and application status remain browser-local.
- Map: Leaflet path remains available, with the project’s offline education-locator fallback for real source-linked records.
- Service worker: cache key bumped for this build to `udaan-shell-v6`.

Run locally with `python -m http.server 8000` and open `http://localhost:8000/`.
