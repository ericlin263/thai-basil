Thai Basil

A single-page website for Thai Basil, a family-owned Thai and Asian fusion restaurant in Colorado Springs.

Live site: https://ericlin263.github.io/thai-basil/

About:

Thai Basil is my parents' restaurant. I built this so they'd have a web presence they actually control, a place where customers can find the menu, the hours, and a phone number without going through a third-party listing.

Features
Filterable menu and category tabs for starters, mains, noodles, and desserts, with dietary tags marking vegetarian, gluten-free, and spicy dishes
Responsive layout + three-column menu grid on desktop that collapses to a single column, with a slide-in navigation panel below 900px
Local SEO and JSON-LD structured data so search engines can read the address, hours, and cuisine directly from the page, plus Open Graph tags for link previews
No dependencies — vanilla HTML, CSS, and JavaScript in one file, no build step or framework
Built with

HTML · CSS (custom properties, grid, flexbox) · JavaScript (DOM APIs, Intersection Observer, event delegation)

Notes on the implementation:

Menu items render through DOM APIs rather than innerHTML string templates, so dish names and descriptions can contain quotes or angle brackets without escaping issues. Menu filtering runs on a single delegated listener on the tab container instead of inline onclick handlers, and the scroll handler is throttled with requestAnimationFrame.

Roadmap
 Food photography throughout, and a preview image for shared links
 Custom domain
 Online ordering, if the restaurant wants it
