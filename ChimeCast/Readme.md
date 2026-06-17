# ChimeCast

## Overview

ChimeCast is an interactive weather visualization application that transforms real world weather conditions into motion and sound. Instead of presenting weather solely through numbers and charts, ChimeCast provides a sensory experience by converting wind intensity into animated wind chimes and procedurally generated audio.

Users can search for locations worldwide and experience local weather conditions through dynamic visuals, synthesized chime sounds, and interactive mapping.

## Features

* Global location search using live geocoding services
* Real-time weather data retrieval
* Animated wind chimes driven by actual wind speed
* Procedural sound synthesis using the Web Audio API
* Multiple chime material presets (Metal, Crystal, Bamboo/Wood, Japanese Fūrin)
* Interactive map with location markers
* Responsive design for desktop and mobile devices

## Technology Stack

* HTML5
* CSS3
* JavaScript (ES6+)
* Web Audio API
* Open-Meteo Geocoding API
* Open-Meteo Weather Forecast API
* Leaflet.js
* CARTO Voyager Map Tiles

## How It Works

1. The user searches for a location.
2. The Open-Meteo Geocoding API converts the location into geographic coordinates.
3. The Open-Meteo Weather API retrieves live weather information.
4. Wind speed values drive the animation behaviour of the wind chimes.
5. The Web Audio API generates dynamic chime sounds based on the selected material preset.
6. The location is displayed on an interactive map using Leaflet.js.

## My Contributions

* Conceived and designed the ChimeCast project idea
* Defined the application's user experience and feature set
* Planned the weather-to-sound interaction concept
* Used AI-assisted development to accelerate implementation
* Integrated weather, geocoding, audio, and mapping components
* Debugged functionality and resolved implementation issues
* Tested application behaviour across different weather scenarios
* Organized project structure and documentation

## Challenges

* Translating real-world wind speeds into realistic visual motion
* Generating natural-sounding chime tones through code
* Managing asynchronous API requests and error handling
* Maintaining responsive layouts across devices

## Future Improvements

* Save favourite locations
* Historical weather playback
* Additional chime styles and sound profiles
* Progressive Web App (PWA) support
* Enhanced environmental visual effects

##screenshots
* dashboard is displayed in Chimecast dashboard,chimes.png
* weather display of kyoto in japan is shown in ChimeCast weather display.png
