# Plate Load Test Visuals

Engineering-grade dashboard package for scanned plate load test field data.

## Contents

- `index.html` - self-contained interactive engineering dashboard with five views.
- `plate_load_readings.csv` - transcribed PLT1 and PLT2 readings from the scan.
- `powerbi_measures.dax` - Power BI measures for settlement, stiffness, recovery and gauge variance.
- `powerbi_theme.json` - clean STS-style Power BI theme.
- `server.mjs` - optional local preview server.

## Engineering Note

The source worksheet did not contain handwritten elapsed-time values. The dashboard therefore uses an inferred 5-minute stage-sequence proxy for the time progression page and labels it clearly. Replace `InferredElapsedMin` if stopwatch readings become available.
