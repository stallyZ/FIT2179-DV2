# Submission Draft

## Proposed Title

Free Fares, Full Platforms? Victoria's Public Transport Demand and Network Pressure in 2026

## Domain / Why / Who / What / How

This visualisation focuses on recent public transport demand in Victoria, Australia. In 2026, the Victorian Government made public transport free from 31 March to 31 May, followed by half-price fares from 1 June to 1 January 2027. The visualisation asks where extra demand would likely be felt first by looking at the network's recent baseline: which modes carry the most passengers, which day types create the strongest pressure, and which metropolitan train stations already concentrate the largest passenger volumes.

The intended audience is the average Victorian or Australian viewer, especially commuters, students and occasional public transport users. The design avoids technical transport jargon and focuses on everyday questions: which services are busiest, when are they busiest, and where might crowding be most visible?

The data comes from Victorian Government Department of Transport and Planning open datasets. The first dataset is monthly average patronage by day type and mode, covering metro train, tram, metro bus, regional train and regional bus records up to January 2026. The second dataset is the FY2024-25 annual metropolitan train station patronage file, which includes station entries, coordinates and time-band patronage. Transport Victoria's free-fare announcement is used as policy context.

The page uses Vega-Lite charts including line charts, grouped bar charts, heatmaps, ranked bar charts, scatterplots and a geographic point map. I used different chart types because each one answers a different question. The line chart shows change over time, the map shows where busy stations are, and the heatmap makes day-type patterns easier to compare. The station ranking and time-band charts also help show why some locations may experience pressure earlier than others.

Important caveat: the latest public patronage table used here reaches January 2026, so the 31 March to 31 May 2026 free-fare period is not treated as final measured patronage. It is shown as current policy context rather than used to invent unavailable data.

## Sketch Plan

Sketch file prepared from hand-drawn photo:

```text
sketch-yuxin-zhang.pdf
```

The sketch shows one long scrolling page with four sections:

1. Title and key numbers.
2. Mode and day-type baseline charts.
3. Station map and busiest-station ranking.
4. Peak-time and weekend-pressure comparison, ending with the main takeaway.
