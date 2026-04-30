# Wear OS Security Shift Tracker

A wrist-first **Wear OS + Android companion app** for recording security shifts
with **start/stop timing, job selection, and voice notes**.

Designed for:
- OnePlus Watch 3 (Wear OS)
- Samsung Galaxy S25 Ultra

---

## Core Features

### Watch (Wear OS)
- Start / Stop shift timer
- Select job or site from synced list
- Record voice notes during an active shift
- Wear OS Tile for instant access
- Optional complication for status

### Phone (Android)
- Manage job / site list
- View shift history
- Play or transcribe voice notes
- Export shifts to CSV
- Local storage (offline-first)

---

## Typical Workflow

1. Guard starts shift from watch Tile
2. Selects job or patrol area
3. Records voice notes as needed (incidents, observations)
4. Stops shift
5. Data syncs to phone automatically
6. Export or review later

---

## Data Collected Per Shift

- Date
- Start time
- End time
- Duration
- Job / site
- Voice note audio files
- Optional transcription (phone-side)

---

## Tech Stack

- Kotlin
- Wear OS (Compose for Wear OS)
- Android (Room database)
- MediaRecorder (audio)
- Data Layer API (watch ↔ phone sync)

---

## Status

🟡 Specification & design complete  
🟡 Implementation pending  

This repository is intentionally **spec-first** to allow
clean, testable development or easy handoff to a developer.
