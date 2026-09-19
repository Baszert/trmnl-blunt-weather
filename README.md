# Blunt Weather

A weather dashboard that may or may not call you names. One brutally honest line about today's weather, plus the numbers you actually need.

<a href="https://trmnl.com/recipes/305453"><img width="150" alt="Works with TRMNL" src="https://trmnl.com/images/brand/badges/light/works-with-trmnl/trmnl-badge-works-with-light.svg" /></a>

## Features
- A (rude) mood line per weather type, different on every refresh
- Rain warning when the chance of rain is above 50%
- Temperature, feels-like, sunrise and sunset

## Settings
Latitude, longitude and temperature unit (°C / °F).

Data from [Open-Meteo](https://open-meteo.com/) via a small caching proxy. Contains strong language.

### Develop locally

Templates and settings live in [`src/`](src/), ready for [trmnlp](https://github.com/usetrmnl/trmnlp):

```sh
gem install trmnl_preview
trmnlp serve
```

Questions or ideas? trmnl@achtnegen.nl or @Bastronautica on Discord.
