# Mapwork

Mapwork is an interactive job-discovery demo that puts opportunities on a nationwide map. Browse jobs by state, industry, work arrangement, and employment type, then save interesting roles for later.

## Features

- Nationwide map coverage across all 50 state capitals
- Dark, light, and satellite map styles
- State, industry, job type, remote, and hybrid filters
- Search, sorting, salary markers, and job detail panels
- Saved Jobs stored locally in the browser
- Notification, message, and account-menu interface
- Responsive single-file HTML implementation

## Run locally

No build step is required. Open `mapwork-jobs.html` directly, or serve the folder with any local web server:

```bash
python -m http.server 4173
```

Then visit `http://localhost:4173/mapwork-jobs.html`.

## Data note

The current listings are demonstration data used to showcase the interface. Source labels and job details should not be interpreted as verified, active openings. A production version should connect to licensed job-board APIs or employer career feeds and validate listing status, locations, and deadlines.

## Technology

Mapwork uses plain HTML, CSS, JavaScript, Leaflet, and Esri map tiles. No framework, build tooling, or map API key is required for the demo.

