# Environet Pest Control landing page concept

A responsive, static landing page for the Makati City branch. Open `index.html` in a browser or serve this directory with a static web server.

## Design direction

The visual idea is an inspection story: a full-bleed technician photograph with a viewfinder motif, a search-friendly service tagline, a layered diagnostic panel, and an asymmetrical service mosaic. The hero settles into place on load; the diagnostic trace draws when it enters view. Motion is removed for visitors who prefer reduced motion.

## Content and assets

- The logo and technician photographs were supplied for this task. Original copies are retained in `assets/source-home-treatment.png` and `assets/source-site-treatment.png`. The two `*-expanded.jpg` assets were AI-expanded from those originals to suit the hero and service tile. Review the extended surroundings before any public use.
- Company history, service categories, and residential/commercial/industrial scope were checked against [Environet’s website](https://environet.com.ph/) and [Makati location page](https://environet.com.ph/location/environet-pest-control-makati-city/).
- The phone and address follow the supplied Makati Google listing screenshot. Confirm them with Environet before publication.
- The composition drew broad inspiration from [Awwwards’ image-background scroll example](https://www.awwwards.com/inspiration/text-with-image-background-scroll-effect-oic-design) and [dynamic editorial layout example](https://www.awwwards.com/inspiration/dynamic-layout-luca-dini); no layout or assets were copied.

## Scope

All actions are ordinary links: direct phone call, Google Maps search, and Environet’s existing website. There is no form backend, booking system, analytics, or production deployment in this concept.

## Validation

Checked the page in a browser at 375px, 768px and desktop widths, including the mobile menu, image loading, horizontal overflow, and console errors. `node --check script.js` and static anchor/asset checks also passed.
