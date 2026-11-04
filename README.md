# TFR: Summer and Crossbows

A submod for **The Fire Rises** (Hearts of Iron IV, 1.19).

## Contents so far
- **PMC "Wagner"** (`WAG`) – new raw country, led by Yevgeny Prigozhin , Wagner emblem flag, national spirits "Private Military Company" and "Best in Hell".
- Focus tree (6 focuses with icons) with events, decisions (Weapons from Moscow, Internet Research Agency), aircraft and Libyan oil.
- Russian puppet with military access both ways.
- Division **PMC Wagner 1** (template "PMC Wagner"), fully equipped with Russian-made equipment.
- General **Dmitriy Utkin** (all stats 4).
- **Central African Republic map rework**: TFR's 20 CAR provinces split into 44 provinces around real towns, grouped into the 17 real prefectures (states 778, 779, 660 reused, new states 1495-1508). Rebel (CPC) areas kept as in TFR. Railway Bangui-Chad re-routed.
- **Wagner Airbase** (state 1509, province 15017): small Wagner-owned tile next to Bangui with a level 2 air base.
- **Molkino** – new small state (ID 1494, province 14992) in Krasnodar Krai, carved out of Krasnodar province 3734.

## Notes for updating
The map files in `map/` (`provinces.bmp`, `definition.csv`, `buildings.txt`, `railways.txt`,
`strategicregions/135-Taman Region.txt`, `strategicregions/183-Central Africa.txt`) are copies of
TFR's with Molkino and the CAR rework added. State files 778, 779 and 660 override TFR's. When TFR updates its map, re-apply the change on top of the new files.
