# WattCost.org

A free appliance electricity cost calculator and energy reference tool.

🔗 **[wattcost.org](https://wattcost.org)**

## What it does

Enter any appliance's wattage and daily usage hours. WattCost calculates the exact electricity cost per hour, day, month, and year — at your local electricity rate.

Electricity rates are auto-detected from your browser locale and can be refined by country, US state, or Canadian province. Your rate preference is saved locally so you never have to re-enter it.

## Calculators included

- Space Heater
- Central Air Conditioner
- Portable Air Conditioner
- Heat Pump
- Dehumidifier
- Ceiling Fan
- Refrigerator & Chest Freezer
- Dishwasher
- Microwave, Coffee Maker, Electric Oven
- Electric Clothes Dryer & Washing Machine
- Gaming PC, Desktop PC, Laptop
- LED Television
- Wi-Fi Router & Home Server / NAS
- Pool Pump & Hot Tub
- Electric Water Heater
- LED Light Bulb
- Electric Blanket & Hair Dryer
- Aquarium Heater
- EV Charging Cost Calculator
- Battery & Portable Power Station Runtime Calculator
- Solar Panel Output Calculator

## Electricity rates

Pre-loaded rates for:
- **United States** — all 50 states + DC (EIA April 2026)
- **Canada** — all provinces
- **Europe** — 18 countries (Eurostat H1 2025)
- **Rest of world** — Australia, Japan, South Korea, Brazil, Mexico, Argentina, India, South Africa, Singapore, New Zealand

## Features

- Auto-detects your country from browser locale — no permission popup
- Country / state / province selector with real rate data
- Manual rate override — type your exact $/kWh from your bill
- Rate preference saved in localStorage across sessions
- Cost breakdown table by daily usage hours
- Full appliance reference table on the homepage
- ADA/WCAG AA compliant — min 14px fonts, contrast >= 4.5:1
- All calculations run locally in the browser — no data sent to servers
- No sign-up required

## Tech

- PHP 7.2+ with Apache mod_rewrite for clean URLs (`/space-heater-cost-to-run`)
- JSON appliance catalog — one template renders all 30+ appliance pages
- Vanilla JS calculator — no frameworks
- IBM Plex Sans + IBM Plex Mono (Google Fonts)
- Google AdSense — keeps the site free

## License

Content and design © 2026 WattCost.org. Calculator logic is open for reference.
