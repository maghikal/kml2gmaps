# TrailLink

A static, client-side KML-to-Google-Maps navigation-link generator. No API key, build step, or server is required.

## Deploy to GitHub Pages

1. Put these files in a GitHub repository and push to `main`.
2. In **Settings → Pages**, select **Deploy from a branch**, then choose `main` and `/ (root)`.
3. Save. GitHub will publish `index.html` as the site.

The map uses OpenStreetMap tiles and Leaflet from a CDN. KML files are parsed only in the browser.

## Notes

Google Maps URL waypoint limits vary by device and Maps client. TrailLink defaults to eight intermediate waypoints; adjust the slider if a specific destination supports a different limit.
