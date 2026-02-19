---
title: 'Weather Dashboard'
date: 2025-10-22T10:00:00-00:00
lastmod: 2025-10-22T10:00:00-00:00
description: 'A responsive weather dashboard that displays current conditions and forecasts. Built with vanilla JavaScript and a public weather API.'
tags: ['javascript', 'api', 'frontend']
tech: ['JavaScript', 'HTML', 'CSS', 'OpenWeather API']
github: 'https://github.com/erikflowers/weather-icons'
demo: 'https://openweathermap.org/'
type: 'projects'
---

A clean, responsive weather dashboard that shows current weather and a five-day forecast for any city.

## Features

The dashboard displays temperature, humidity, wind speed, and weather conditions. A five-day forecast shows daily highs, lows, and expected conditions.

### Location Search

Users search by city name. The app geocodes the city and fetches weather data from the OpenWeather API. Recent searches are saved in local storage for quick access.

### Responsive Design

The layout adapts to mobile, tablet, and desktop viewports. The forecast grid stacks vertically on small screens and displays horizontally on larger ones.

### Accessibility

All weather icons have descriptive alt text. Color is not used as the sole indicator for any information. The interface is fully keyboard navigable.

## Technical Details

Built with vanilla JavaScript and no frameworks. The fetch API handles data retrieval. CSS Grid provides the responsive layout. No build tools are required.
