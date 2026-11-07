# Roof pitch chart: 1/12 to 24/12 in degrees, slope and rafter length

Roof pitch is the rise in inches for every 12 inches of run: a 6/12 roof climbs 6" per foot, which is 26.6° and a 50% slope. The chart gives the angle, slope, rafter cuts and rafter length per foot of run for every pitch from 1/12 to 24/12.

Web page: [https://klmlabs.app/construction-calculator/roof-pitch-chart/](https://klmlabs.app/construction-calculator/roof-pitch-chart/)  
Printable PDF (US Letter, one page): [roof-pitch-chart.pdf](./roof-pitch-chart.pdf)

## Roof pitch to degrees, slope and rafter length, 1/12 to 24/12

Data: [roof-pitch.csv](./roof-pitch.csv)

**How the numbers are worked out:** Angle = arctan(pitch ÷ 12), the roof’s angle and the rafter’s plumb cut; seat cut = 90° − the plumb cut. Slope = pitch ÷ 12 as a percent. Rafter per foot of run = √(12² + pitch²) inches, to the nearest 1/16" (≈ when rounded); the multiplier is the same length in feet, to 4 places. Rafter lengths are line lengths with no overhang.

Rows shaded on the web page and PDF are in bold here.

| Pitch | Angle (plumb cut) | Seat cut | Slope | Rafter per foot of run | Multiplier |
|---|---|---|---|---|---|
| 1/12 | 4.8° | 85.2° | 8.3% | ≈ 12-1/16" | 1.0035 |
| 2/12 | 9.5° | 80.5° | 16.7% | ≈ 12-3/16" | 1.0138 |
| 3/12 | 14° | 76° | 25% | ≈ 12-3/8" | 1.0308 |
| **4/12** | 18.4° | 71.6° | 33.3% | ≈ 12-5/8" | 1.0541 |
| 5/12 | 22.6° | 67.4° | 41.7% | 13" | 1.0833 |
| **6/12** | 26.6° | 63.4° | 50% | ≈ 13-7/16" | 1.118 |
| 7/12 | 30.3° | 59.7° | 58.3% | ≈ 13-7/8" | 1.1577 |
| **8/12** | 33.7° | 56.3° | 66.7% | ≈ 14-7/16" | 1.2019 |
| 9/12 | 36.9° | 53.1° | 75% | 15" | 1.25 |
| 10/12 | 39.8° | 50.2° | 83.3% | ≈ 15-5/8" | 1.3017 |
| 11/12 | 42.5° | 47.5° | 91.7% | ≈ 16-1/4" | 1.3566 |
| **12/12** | 45° | 45° | 100% | ≈ 17" | 1.4142 |
| 13/12 | 47.3° | 42.7° | 108.3% | ≈ 17-11/16" | 1.4743 |
| 14/12 | 49.4° | 40.6° | 116.7% | ≈ 18-7/16" | 1.5366 |
| 15/12 | 51.3° | 38.7° | 125% | ≈ 19-3/16" | 1.6008 |
| 16/12 | 53.1° | 36.9° | 133.3% | 20" | 1.6667 |
| 17/12 | 54.8° | 35.2° | 141.7% | ≈ 20-13/16" | 1.7341 |
| 18/12 | 56.3° | 33.7° | 150% | ≈ 21-5/8" | 1.8028 |
| 19/12 | 57.7° | 32.3° | 158.3% | ≈ 22-1/2" | 1.8727 |
| 20/12 | 59° | 31° | 166.7% | ≈ 23-5/16" | 1.9437 |
| 21/12 | 60.3° | 29.7° | 175% | ≈ 24-3/16" | 2.0156 |
| 22/12 | 61.4° | 28.6° | 183.3% | ≈ 25-1/16" | 2.0883 |
| 23/12 | 62.4° | 27.6° | 191.7% | ≈ 25-15/16" | 2.1619 |
| 24/12 | 63.4° | 26.6° | 200% | ≈ 26-13/16" | 2.2361 |

## Common rafter length by building span and pitch (line length, no overhang)

Data: [rafter-span.csv](./rafter-span.csv)

**How the numbers are worked out:** The run is half the span. Length = run × √(144 + pitch²) ÷ 12, from the outside of one wall’s top plate to the ridge line, before any ridge-board deduction or overhang, to the nearest 1/16".

| Building span | 4/12 | 6/12 | 8/12 | 10/12 | 12/12 |
|---|---|---|---|---|---|
| 12 ft | ≈ 6' 3-7/8" | ≈ 6' 8-1/2" | ≈ 7' 2-9/16" | ≈ 7' 9-3/4" | ≈ 8' 5-13/16" |
| 16 ft | ≈ 8' 5-3/16" | ≈ 8' 11-5/16" | ≈ 9' 7-3/8" | ≈ 10' 4-15/16" | ≈ 11' 3-3/4" |
| 20 ft | ≈ 10' 6-1/2" | ≈ 11' 2-3/16" | ≈ 12' 0-1/4" | ≈ 13' 0-3/16" | ≈ 14' 1-11/16" |
| 24 ft | ≈ 12' 7-13/16" | ≈ 13' 5" | ≈ 14' 5-1/16" | ≈ 15' 7-7/16" | ≈ 16' 11-5/8" |
| 28 ft | ≈ 14' 9-1/16" | ≈ 15' 7-13/16" | ≈ 16' 9-15/16" | ≈ 18' 2-11/16" | ≈ 19' 9-9/16" |
| 32 ft | ≈ 16' 10-3/8" | ≈ 17' 10-11/16" | ≈ 19' 2-3/4" | ≈ 20' 9-15/16" | ≈ 22' 7-1/2" |

## Citations (as on the web page)

- IRC 2021 R905 minimum slopes: asphalt shingles 2/12 (double underlayment from 2/12 up to 4/12), clay and concrete tile 2-1/2/12, metal roof shingles 3/12, mineral-surfaced roll roofing 1/12, slate 4/12, wood shingles and wood shakes 3/12. Source: https://up.codes/viewer/colorado/irc-2021/chapter/9/roof-assemblies (the 2021 IRC as adopted without amendments; read 2026-11-06)
- IRC 2024 keeps the R905 minimum slopes (R905.2.2 to R905.8.2) and R802.4.1 rafter sizing with the same numbers and values. Source: https://up.codes/viewer/texas/irc-2024/chapter/9/roof-assemblies and https://up.codes/viewer/texas/irc-2024/chapter/8/roof-ceiling-construction (the 2024 IRC adopted without amendments; read 2026-11-07)
- IRC 2021 R802.4.1: rafters are sized from the rafter span tables R802.4.1(1) to (8), or the AWC Span Tables for other grades, species and loads. Source: https://up.codes/viewer/colorado/irc-2021/chapter/8/roof-ceiling-construction (read 2026-11-06)
- A common rafter's line length runs to the ridge's center; it is shortened by half the ridge thickness, measured level (at right angles to the plumb cut). Source: Griffith, Carpentry §19 (https://chestofbooks.com/home-improvement/woodworking/Ira-S-Griffith/Carpentry/19-Ridge-Piece.html); Sloggatt, Common Rafter Framing (https://www.thisiscarpentry.com/2012/11/09/common-rafter-framing/); both read 2026-11-07

## Sources

- [International Code Council: 2021 IRC, Chapter 9, Roof Assemblies (R905 minimum slopes; the official text)](https://codes.iccsafe.org/content/IRC2021P2/chapter-9-roof-assemblies)
- [UpCodes: 2021 IRC Chapter 9 as adopted without amendments (R905.2.2, R905.3.2, R905.4.2, R905.5.2, R905.6.2, R905.7.2, R905.8.2, read in full)](https://up.codes/viewer/colorado/irc-2021/chapter/9/roof-assemblies)
- [UpCodes: 2021 IRC Chapter 8, Roof-Ceiling Construction (R802.4.1 rafter size)](https://up.codes/viewer/colorado/irc-2021/chapter/8/roof-ceiling-construction)
- [Ira S. Griffith, Carpentry, §19 Ridge Piece: a common rafter is shortened by "one-half the thickness of the ridge measured at right angles to the plumb cut"](https://chestofbooks.com/home-improvement/woodworking/Ira-S-Griffith/Carpentry/19-Ridge-Piece.html)
- [Mike Sloggatt, Common Rafter Framing, THISisCarpentry (the ridge's full width comes off the building width before it is halved into each rafter's run)](https://www.thisiscarpentry.com/2012/11/09/common-rafter-framing/)
- [UpCodes: 2024 IRC Chapter 9 as adopted without amendments (Texas Windstorm Insurance Association; R905 minimum slopes)](https://up.codes/viewer/texas/irc-2024/chapter/9/roof-assemblies)
- [American Wood Council: Span Tables for Joists and Rafters, 2024 edition](https://awc.org/resources/2024-span-tables/)

## Notes

- Every cell was generated by running the klmlabs.app chart code, which uses the formulas of Construction Calculator 1.1.1 (an iPhone and iPad app by KLM Labs). Nothing was typed in by hand.
- A printed chart is a guide: measure on site, and check your local building code for roofs. Cities, counties and states adopt a code edition, often with amendments; this is a summary of the model code, not legal advice.
- License: CC BY 4.0. Credit: "KLM Labs, klmlabs.app".
