---
system:
  name: "Hurricane Isaias"
  basin: "AL"
  number: "09"
  year: 2020
advisory:
  number: 30
  issuing_office: "NWS National Hurricane Center Miami FL"
  issued_at: "2020-08-03T23:00:00Z"
  forecaster: "Berg"
position:
  latitude: 33.0
  longitude: -78.5
  coordinates_str: "33.0N 78.5W"
  movement_dir: 350
  movement_speed_kt: 19
metrics:
  max_sustained_winds_kt: 75
  max_sustained_winds_mph: 85
  gusts_kt: 90
  min_pressure_mb: 988
  category: 1
watches_warnings:
  hurricane_warning:
    - "South Santee River SC to Surf City NC"
  tropical_storm_warning:
    - "Altamaha Sound GA to South Santee River SC"
    - "Surf City NC to Mouth of the Delaware Bay"
tags:
  - weather/nhc
  - tropical/isaias
  - status/archived
---

# Hurricane Isaias — NHC Advisory #30

> [!WARNING]
> **Hurricane Warning in Effect:** Life-threatening storm surge and hurricane-force winds expected across coastal North and South Carolina. Evacuation orders in effect for low-lying areas.

## Advisory Metrics Summary

| Parameter | Metric Value | NWS Text Standard |
| :--- | :--- | :--- |
| **Location** | `33.0N 78.5W` | ~60 mi SSW of Myrtle Beach SC |
| **Max Winds** | `75 kt` (85 mph) | Category 1 Hurricane |
| **Movement** | `NNW (350°) at 19 kt` | Accelerating North-Northeast |
| **Min Pressure** | `988 mb` (29.18 inHg) | Falling |

---

## Technical Discussion & Forecast Track

```mermaid
graph LR
    A[Adv #29: 70 kt] --> B[Adv #30: 75 kt<br>Landfall SC/NC]
    B --> C[Adv #31: 50 kt<br>Inland Mid-Atlantic]
    B --> D{Impact Type}
    D -->|Coastal| E[Storm Surge: 3-5 ft]
    D -->|Inland| F[Heavy Rain: 4-8 in]
