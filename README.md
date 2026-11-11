# Jet A Fuel Calculator (G550)

A single-page refuelling calculator for the Gulfstream G550: weight ↔ volume conversion for Jet A, with temperature-based density correction. Enter what is in the tanks and what you want, and it tells you how much to order in pounds or kilograms, US gallons (for the FBO) and liters (for the truck). The interface is in Traditional Chinese with English labels.

**Live demo:** https://shainyhsu.github.io/fuel/

## Features

- **lbs / kg switch** for all weights; density shows in lb/gal or kg/L to match, and entered values convert when you switch
- **Fuel to uplift** from remaining fuel and desired total, shown in weight, US gallons and liters, plus the total fuel after uplift in US gallons and liters
- **Type into any uplift field** (weight, gallons or liters): the other two and the desired total update automatically
- **Ticket check:** enter the gallons first, then overwrite the weight from the fuel ticket, and the page works out the actual density and the matching fuel temperature
- **Temperature-based density:** FAA/AFM baseline 6.75 lb/gal at 0 °C, about −0.0058 lb/gal per °C; manual density override available
- **Remaining fuel temperature:** shows the remaining fuel's volume and density, and the mass-weighted average temperature of the fuel after uplift
- **G550 fuel limits on screen:** max usable fuel (lbs, kg, US gal, L), left/right tank capacity, takeoff and in-flight imbalance limits, max ramp and takeoff weights; the uplift weight turns amber if the desired total exceeds 41,300 lbs
- **Light/dark theme** toggle at the top right (dark by default, remembered on your device)
- **Two-column layout on wide screens** (calculator on the left, uplift and limits on the right); single column on phones
- Pinch-to-zoom allowed on mobile
- Page title, description, canonical link, Open Graph and structured data for search engines and link previews

## How to use

1. Choose units (lbs or kg)
2. Enter remaining fuel, and optionally its temperature
3. Enter the uplift fuel temperature (or a density from the truck)
4. Enter the desired total fuel, or type the uplift directly in weight, gallons or liters
5. Read US gallons (for the FBO) and liters (for the truck)
6. Optional: after fuelling, keep the gallons and enter the ticket weight to back out the actual density and temperature

Always cross-check with truck density and aircraft fuel gauges.

## Tech

Single HTML page (HTML, CSS and plain JavaScript) on GitHub Pages. Fully client-side: no build step, no server, no tracking. The only thing stored is your theme choice, in your browser.

## Version history

Newest first. Times are Taiwan time (UTC+8). Also kept in [CHANGELOG.md](CHANGELOG.md).

- V13 | 2026-11-11 10:07 | New license terms: free to use in a browser for personal, work, school or club use, and the results you make are yours to share; copying, paid services built on it, and AI training need written permission. A License link sits at the bottom of the page
- V12 | 2026-11-10 00:18 | Added a link-preview image (1200×630) so shared links show a picture in LINE, Facebook and other apps.
- V11 | 2026-11-09 11:24 | Wide-screen layout: the two top cards share equal width and height, and the G550 fuel limitations span the full width below, so the page fits on one screen.
- V10 | 2026-11-09 10:14 | Added a two-column layout for wide screens and an All Rights Reserved license.
- V9 | 2026-11-09 09:23 | Added a light/dark theme toggle at the top right, dark by default.
- V8 | 2026-11-08 20:28 | Added search-engine and link-preview information, and allowed pinch-to-zoom on mobile.
- V7 | 2026-11-05 18:50 | Minor fixes (header position tried lower on the page, then restored).
- V6 | 2026-11-05 18:42 | Added the mass-weighted average fuel temperature after uplift.
- V5 | 2026-11-05 18:34 | Redesigned the page with a lbs/kg switch, a remaining-fuel temperature field that shows its volume and density, and kg in the limits table.
- V4 | 2026-11-05 17:52 | Renamed back to Jet A Fuel Calculator and added the ticket check that works out density and temperature from gallons and ticket weight.
- V3 | 2026-11-05 14:26 | Made the uplift fields editable so you can type in lbs, gallons or liters and the rest updates, with the results card always visible.
- V2 | 2026-11-04 22:46 | Renamed the page to Jet A1 Fuel Calculator, with G550 as the subtitle.
- V1 | 2026-11-04 22:35 | First public release: G550 fuel calculator converting remaining and desired fuel in lbs to uplift in US gallons and liters, with fuel-temperature density correction and the G550 fuel limits table.

## License

Copyright (c) 2026 Shainy Hsu. All rights reserved. See [LICENSE](LICENSE).

You may use the published website in your browser for personal use. No copying, reuse, mirroring, scraping, or AI/machine-learning training on any part of this work without written permission.
