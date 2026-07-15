# FallClaim v1.0.0 - case management 2026

> **FallClaim is a browser-based case management system for claims firms, pairing offline local storage, a quantum corpus, and practical workflow tracking in version 1.0.0.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zackx82/fallclaim-case-hub-v1?style=flat-square)](https://github.com/zackx82/fallclaim-case-hub-v1)

---

<p align="center">
  <a href="https://zackx82.github.io/fallclaim-case-hub-v1/">
    <img src="https://img.shields.io/badge/Download-FallClaim%20Latest-brightgreen?style=for-the-badge" alt="Download FallClaim">
  </a>
</p>

> **[Direct Download - FallClaim v1.0.0](https://zackx82.github.io/fallclaim-case-hub-v1/)**

---

[Download Latest Build](https://zackx82.github.io/fallclaim-case-hub-v1/)

---

## Overview

FallClaim is made for claims teams that need structured case handling directly in the browser. It keeps firm, adviser, client, and case records together in one workspace, while preserving availability through offline-first local storage.

It fits teams looking for a sovereign-style, single-file workflow for US claims management. With built-in guideline references, timeline control, and document management, it helps consolidate the information that otherwise gets scattered across spreadsheets, notes, and separate applications.

---

## Features

- Multi-firm, multi-adviser, multi-client, and multi-case management
- Offline operation with local data storage
- Embedded judicial college guideline quantum corpus
- Limitations calculator for case planning
- Part 36 offer tracking
- Protocol workflow tracking
- Fee tracking for claim administration
- Timeline and document tracking across matters

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/zackx82/fallclaim-case-hub-v1.git
2. Open the project in a modern web browser.
3. If you are using a local copy, keep the files together as a single package so offline storage and browser persistence remain available.
4. Launch the main HTML entry file in your browser.

For a hosted build, use the download link above and open the application directly from the published site.

---

## Usage

Begin by creating or importing your firm, adviser, client, and case records. After that, work through each matter by logging timeline events, documents, fees, and offer information as the case progresses.

Typical workflow:
1. Create a new case.
2. Add participants and case metadata.
3. Review guideline and quantum references.
4. Track limitation dates and protocol steps.
5. Record Part 36 offers and fee activity.
6. Store documents and update the timeline as events occur.

---

## Configuration

FallClaim operates with browser-based local storage, including IndexedDB for persistent data in the browser.

When build-specific settings are available, they are generally managed inside the application UI rather than in a separate configuration file. Since the tool follows a single-file style, deployment and data persistence are meant to remain close to the browser runtime.

---

## Requirements

- A modern web browser
- JavaScript enabled
- Local storage support, including IndexedDB
- Enough disk space for saved case data and documents
- Internet access only if you are loading the hosted build or external assets

---

## FAQ

**Does it work offline?**  
Yes. The project is designed for offline operation with local data storage.

**What kind of work is it aimed at?**  
It is focused on claims firm case management, especially US claims workflows.

**Can I use it for multiple firms or cases?**  
Yes. The feature set includes multi-firm, multi-adviser, multi-client, and multi-case handling.

**Where is data stored?**  
Data is stored locally in the browser, using browser storage mechanisms such as IndexedDB.

**How do I update it?**  
Use the latest published build from the download link above, or pull the newest repository changes and reopen the app in your browser.

**What if something does not load correctly?**  
Check browser support, clear local site data if needed, and confirm that JavaScript and persistent storage are enabled.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
