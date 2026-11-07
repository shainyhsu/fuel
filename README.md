# Jet A Fuel Calculator

Weight ↔ volume conversion for Jet A with temperature-based density correction.

**Live demo:** https://shainyhsu.github.io/fuel/

## Features

- Remaining fuel and uplift: lbs ↔ kg ↔ US gallons ↔ liters
- Density adjusted for fuel temperature (FAA baseline 6.75 lb/gal at 0°C, about −0.0058 lb/gal per °C)
- Manual density override
- G550 fuel limits on screen (max usable, left/right tanks, imbalance limits, max weights)

## How to use

1. Choose units (lbs or kg)
2. Enter remaining fuel and fuel temperature (or density)
3. Enter target total fuel or fuel to uplift
4. Read US gallons (for the FBO) and liters (for the truck)

Always cross-check with truck density and aircraft fuel gauges.

## Tech

Single HTML page on GitHub Pages. Fully client-side.
