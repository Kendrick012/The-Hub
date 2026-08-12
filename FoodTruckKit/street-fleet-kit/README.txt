STREET FLEET KIT — food truck sites
===================================

sites/      Four finished, linked pages (keep together in one folder):
            index.html            hub homepage - 3 bands, each links to a truck
            hot-plate.html        dark + mustard smash burger truck
            umami-wagon.html      indigo night-market truck (lantern)
            sprout-and-squeeze.html  light juice truck (harvest wheel)
            Every truck page has: Google Maps embed, menu, reviews,
            business hours, contact, marquee/animations.

blocks/     The copy-paste library. Three styles: truck / umami / sprout.
            Sections: navbar, hero, menu, map, reviews, info (hours+contact),
            footer, marquee (truck style), hub (homepage band).
            ornaments/: rolling-truck, lantern, wheel - animated hero pieces.
            01-startup.html: empty shell with all three styles' tokens and
            the build-order instructions.

WORKFLOW
1. New truck client? Copy the closest sites/ page and swap the content, or
2. Build from scratch: copy 01-startup.html, pick a style, paste blocks
   in order (each block file shows itself when opened in a browser).
3. Maps: replace the iframe q= value with the client's parking spot.
4. Multi-truck client? Stack hub/band.html per truck on an index page.
