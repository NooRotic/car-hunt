# car-hunt

Static used-car search board. Single self-contained `index.html` — no build, no deps.

Listings scraped from Cars.com + CarMax, filtered to PA/DE within ~45 min of 19003.
Photos are hotlinked to the source CDN and will rot as listings sell.

Regenerate: re-scrape, rebuild `_viewer_data.js`, re-inline into `index.html`.
