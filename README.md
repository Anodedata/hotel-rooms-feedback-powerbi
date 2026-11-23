# Hotel Rooms Feedback Dashboard (Power BI)

A dark-theme, multi-page **Power BI** hospitality analytics dashboard built to monitor guest satisfaction across multiple survey channels (**WhatsApp** and **IVRS**) and service dimensions—highlighting the **Room Cleanliness** executive overview.

![Rooms Feedback Executive Overview](assets/rooms-feedback-cleanliness.png)

---

## Executive KPIs & Interactive Controls
* **Total Customers Surveyed:** `30`
* **No Responses:** `1`
* **Interactive Slicers:** Filter dynamically by **Channel** (`IVRS` / `WhatsApp`), **Date Range** (`1/15/2025` – `1/17/2025`), and dropdown category selectors.

---

## Key Analytical Views (Cleanliness Page)

### 1. Feedback Channel Distribution
Donut chart comparing survey participation by channel:
* **WhatsApp:** `16` responses (`53.33%`)
* **IVRS:** `14` responses (`46.67%`)

### 2. Overall Room Cleanliness Breakdown
Horizontal bar chart summarizing guest sentiment across all responses:
* **Good:** `13`
* **Average:** `13`
* **Bad:** `4`

### 3. Channel & Daily Sentiment Trends
* **Daily Cleanliness by Channel (Stacked Column):** Compares `Good`, `Average`, and `Bad` ratings day-by-day (`15`, `16`, `17`) split across `IVRS` and `WhatsApp` to spot channel-specific sentiment patterns.
* **Daily Rating Comparison (Clustered Column):** Tracks daily volume of `Average`, `Bad`, and `Good` feedback side by side to monitor service consistency over time.

---

## Multi-Page Navigation Architecture
Designed as a complete guest-experience suite with bottom tab navigation across seven dedicated views:
`HOME` | `FACILITIES` | `CLEANLINESS` | `SERVICES` | `COMFORT` | `V.F.M` | `O.A. SATISFACTION`

---

## Tech Stack
* **BI Platform:** Microsoft Power BI
* **Design & UX:** Dark-mode executive UI, custom pill-style page navigation, channel toggle buttons, and color-coded sentiment visuals (`Good`, `Average`, `Bad`)
