# Skyline & Scoreboard

A dark, responsive weather and sports dashboard for Parker, Colorado and Tempe, Arizona.

## Features

- Live current conditions and 10-day forecasts from Open-Meteo
- Football schedules for the Arizona Cardinals, Arizona State, and Arizona Wildcats
- Basketball schedules for the Phoenix Suns, Arizona State, and Arizona Wildcats
- Season-wide calendar grids with team and opponent logos
- Same-day games panel
- Mountain Standard Time display
- ESPN live schedule data with fallback entries when a feed is not published

## Run locally

Open `WeatherSchedule.html` in a browser, or serve the repository directory with any static web server. Browser requests to the public weather and sports endpoints require network access.

## Data sources

- Weather: Open-Meteo API
- Sports schedules and logos: ESPN public endpoints and ESPN CDN

The ESPN endpoints are suitable for a prototype and may change or rate-limit browser requests.
