# OpenStreetMap-derived land tiles

`bimini_true_*` and `west_end_true_*` are derived from OpenStreetMap
`place=island` / `place=islet` geometry, built by
`tools/chart/build_osm_truth_tile.py` in the bluepassage repo.

© OpenStreetMap contributors, available under the Open Database License (ODbL).
See https://www.openstreetmap.org/copyright

Every other `*_true_*` tile in this directory is derived from NOAA ENC
`Land_Area` and is unaffected by this notice.

## What these tiles are, and are not

They are a LAND/WATER BOUNDARY at roughly 10m, and nothing else. They carry
no depth, no soundings, no navaids and no hazards, and they must never be
used to decide whether water is deep enough for a vessel. The Bahamian banks
are largely 6-20 feet and we have no survey data for them at all; the router
plans the crossing to the landfall and declines beyond it
(`bahamas_bank_unsurveyed`) for exactly that reason.
