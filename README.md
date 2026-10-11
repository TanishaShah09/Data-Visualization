# F1 Performance Hub (PBIP) — 4 pages, synthetic data

1. Extract the zip fully (Extract All), then open `F1_Hub.pbip` from the extracted folder.
2. Home > Transform data > Edit parameters > set DataFilePath to the full path of
   F1_Synthetic_Qualifying_LapTime_AddOn_80Kplus.xlsx (use Copy as path, remove the quotes) > OK > Apply changes.

Pages: Overview, Drivers, Constructors, Season Trends. Season / Driver / Constructor slicers are synced on all pages.
All data is SYNTHETIC (SYN_ keys). Driver/constructor labels are "SYN D01" / "SYN T01" (derived from the keys).

Edge measures compare against the field average of the selected seasons:
Qualifying Edge (+ = better qualifying position), Q3 Reach Edge, Consistency Edge (+ = smaller spread).

Expected totals (no filters): 11,120 entries, 556 races, 20 drivers, 10 constructors, avg qualifying position 10.48,
avg lap 95.963, fastest lap 76.101, Q3 reach 50.0%.
