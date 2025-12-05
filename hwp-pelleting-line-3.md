---
title: Hwp Pelleting Line 3
parent: Historized Tag Reference
nav_order: 8
---

# Hwp Pelleting Line 3

_3 historized tags._


### Short Tons [1]

**Original label:** `Short Tons [1]`

**Tag path:** `_hwp pelleting line 3_/controller:global/line_3_shift_total`

**Usage in reporting views:**
- `shift_total_view` – Shift-level total tonnage: classifies samples into day/night shifts, picks a last-hour snapshot per shift and tag, adjusts Tag 1 with an assumed rate for a bad window, and outputs short/metric tons.
- `ytd_metric_total_view` – Year-to-date metric tonnage: shift-based tonnage totals converted to metric tons with a manual starting offset.

**Other names / labels:**
- column aliases: `metric_tons`, `short_tons`


### SBH DP 3 [10]

**Original label:** `SBH DP 3 [10]`

**Tag path:** `_hwp pelleting line 3_/controller:global/scavenge_baghouse_dp`

**Usage in reporting views:**
- `dp_dashboard_view` – Differential pressure dashboard: hourly last-sample snapshots for scavenger and DHM baghouse differential pressure tags, with error-code filtering and global error statistics.

**Other names / labels:**
- commented names: `SBH DP 3`


### Line 3 Pellet Mill Running [1100]

**Original label:** `Line 3 Pellet Mill Running [1100]`

**Tag path:** `_hwp pelleting line 3_/controller:global/line_3_pelletmills_running`

**Usage in reporting views:**
- `rco_epd_report_view_single_sample_by_mill` – RCO EPD helper: 15-minute nearest-sample state per mill including RCO status, SCBH status per line, pellet mill running flags, 500 damper, and RCO 3-hour average.

**Other names / labels:**
- commented names: `Line 3 Pellet Mill Running`
