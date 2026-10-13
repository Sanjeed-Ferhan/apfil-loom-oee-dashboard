# APFIL Loom (Unit-01 & Unit-02) — Production Performance / OEE Loss Diagnostic

Single-file HTML dashboard for **APFIL — Loom**, covering **Unit-01** and **Unit-02**, shifts A–C.

## Features
- **Toggle:** Last day (12-Oct-2026) and Month-to-date (Oct 2026)
- OEE KPIs (Availability / Performance / Quality / Overall OEE) vs targets **A90 / P86 / Q97 / OEE75**
- Where time is going (Planned Production Time split Run vs unplanned NPT)
- OEE by unit (Unit-01, Unit-02) + Find-the-bottleneck (OEE factor constraint)
- Top downtime + downtime by category (min)
- **Opportunity Loss = NPT min ÷ cycle time (min/MTR)** → lost output (MTR)
- Production & OEE trend (last 16 days)
- Shift Action Board — downtime reasons with **responsible team** tagging
- Shift OEE and Gemba walk

## Data source
`Production Report` and breakdown tabs of the two APFIL Loom sheets (Unit-01 gid=0 / U1 Breakdown; Unit-02 gid=0 / U2 Breakdown).

## Notes
- OEE = Availability × Performance × Quality.
- Availability = Actual Run Time ÷ Planned Production Time (planned downtime excluded).
- Breakdown/downtime is unplanned only.
- Data through 12-Oct-2026.
