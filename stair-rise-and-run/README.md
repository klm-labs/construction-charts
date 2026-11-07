# Stair rise and run code: IRC 2021 limits with worked layouts

Under the 2021 International Residential Code, a stair riser may be at most 7-3/4" high and a tread at least 10" deep (sections R311.7.5.1 and R311.7.5.2). The chart works out risers, riser height, treads and total run for total rises from 2' to 10', at those limits and at the stricter 7-11 rule.

Web page: [https://klmlabs.app/construction-calculator/stair-rise-and-run/](https://klmlabs.app/construction-calculator/stair-rise-and-run/)  
Printable PDF (US Letter, one page): [stair-rise-and-run.pdf](./stair-rise-and-run.pdf)

## Stairs by total rise: 7-3/4" maximum riser, 10" treads

Data: [stairs-irc.csv](./stairs-irc.csv)

**How the numbers are worked out:** Risers = total rise ÷ 7-3/4", rounded up; riser height = total rise ÷ risers; treads = risers − 1; total run = treads × 10". Stringer = the pitch line, √(riser² + tread²) × risers; angle = arctan(riser ÷ tread). Lengths to the nearest 1/16" (≈ when rounded).

| Total rise | Risers | Riser height | Treads | Total run | Stringer | Angle |
|---|---|---|---|---|---|---|
| 2' 0" | 4 | 6" | 3 | 2' 6" | ≈ 3' 10-5/8" | 31° |
| 2' 6" | 4 | 7-1/2" | 3 | 2' 6" | 4' 2" | 36.9° |
| 3' 0" | 5 | ≈ 7-3/16" | 4 | 3' 4" | ≈ 5' 1-5/8" | 35.8° |
| 3' 6" | 6 | 7" | 5 | 4' 2" | ≈ 6' 1-1/4" | 35° |
| 4' 0" | 7 | ≈ 6-7/8" | 6 | 5' 0" | ≈ 7' 0-7/8" | 34.4° |
| 4' 6" | 7 | ≈ 7-11/16" | 6 | 5' 0" | ≈ 7' 4-7/16" | 37.6° |
| 5' 0" | 8 | 7-1/2" | 7 | 5' 10" | 8' 4" | 36.9° |
| 5' 6" | 9 | ≈ 7-5/16" | 8 | 6' 8" | ≈ 9' 3-5/8" | 36.3° |
| 6' 0" | 10 | ≈ 7-3/16" | 9 | 7' 6" | ≈ 10' 3-1/4" | 35.8° |
| 6' 6" | 11 | ≈ 7-1/16" | 10 | 8' 4" | ≈ 11' 2-7/8" | 35.3° |
| 7' 0" | 11 | ≈ 7-5/8" | 10 | 8' 4" | ≈ 11' 6-3/8" | 37.4° |
| 7' 6" | 12 | 7-1/2" | 11 | 9' 2" | 12' 6" | 36.9° |
| 8' 0" | 13 | ≈ 7-3/8" | 12 | 10' 0" | ≈ 13' 5-5/8" | 36.4° |
| 8' 6" | 14 | ≈ 7-5/16" | 13 | 10' 10" | ≈ 14' 5-3/16" | 36.1° |
| 9' 0" | 14 | ≈ 7-11/16" | 13 | 10' 10" | ≈ 14' 8-13/16" | 37.6° |
| 9' 6" | 15 | ≈ 7-5/8" | 14 | 11' 8" | ≈ 15' 8-3/8" | 37.2° |
| 10' 0" | 16 | 7-1/2" | 15 | 12' 6" | 16' 8" | 36.9° |

## The same rises at a 7" maximum riser and 11" treads (the 7-11 rule)

Data: [stairs-7-11.csv](./stairs-7-11.csv)

**How the numbers are worked out:** Same formulas, with 7" and 11" in place of 7-3/4" and 10".

| Total rise | Risers | Riser height | Treads | Total run | Stringer | Angle |
|---|---|---|---|---|---|---|
| 2' 0" | 4 | 6" | 3 | 2' 9" | ≈ 4' 2-1/8" | 28.6° |
| 3' 0" | 6 | 6" | 5 | 4' 7" | ≈ 6' 3-3/16" | 28.6° |
| 4' 0" | 7 | ≈ 6-7/8" | 6 | 5' 6" | ≈ 7' 6-3/4" | 31.9° |
| 5' 0" | 9 | ≈ 6-11/16" | 8 | 7' 4" | ≈ 9' 7-3/4" | 31.2° |
| 6' 0" | 11 | ≈ 6-9/16" | 10 | 9' 2" | ≈ 11' 8-13/16" | 30.8° |
| 7' 0" | 12 | 7" | 11 | 10' 1" | ≈ 13' 0-7/16" | 32.5° |
| 8' 0" | 14 | ≈ 6-7/8" | 13 | 11' 11" | ≈ 15' 1-1/2" | 31.9° |
| 9' 0" | 16 | 6-3/4" | 15 | 13' 9" | ≈ 17' 2-1/2" | 31.5° |
| 10' 0" | 18 | ≈ 6-11/16" | 17 | 15' 7" | ≈ 19' 3-1/2" | 31.2° |

## Citations (as on the web page)

- IRC 2021 R311.7: riser not more than 7-3/4 in. (R311.7.5.1) and tread not less than 10 in. (R311.7.5.2), each varying by no more than 3/8 in. in a flight; headroom 6 ft 8 in. (R311.7.2); width 36 in. (R311.7.1); a flight rises no more than 12 ft 7 in. (R311.7.3); nosing 3/4 to 1-1/4 in., not required where treads are 11 in. or more (R311.7.5.3); a handrail on at least one side with four or more risers, 34 to 38 in. high (R311.7.8, R311.7.8.1). Source: https://up.codes/viewer/colorado/irc-2021/chapter/3/building-planning (the 2021 IRC as adopted without amendments; read 2026-11-06)
- IRC 2024 keeps the same stair limits, renumbered: R318.7.1 width 36 in., R318.7.2 headroom 6 ft 8 in., R318.7.3 rise 12 ft 7 in., R318.7.5.1 riser 7-3/4 in., R318.7.5.2 tread 10 in., R318.7.5.3 nosing 3/4 to 1-1/4 in. (none needed at 11 in.), R318.7.8 handrail with four or more risers, R320.2 handrail height 34 to 38 in. Source: https://up.codes/viewer/texas/irc-2024/chapter/3/building-planning (Texas Windstorm Insurance Association Residential Code 2024, which adopts the 2024 IRC without amendments; read 2026-11-07)
- Residential Code of New York State 2025 (the 2024 IRC with amendments) R318.7.5.1: risers not more than 8-1/4 in.; R318.7.5.2: treads not less than 9 in. Source: https://up.codes/viewer/new_york/irc-2024/chapter/3/building-planning (read 2026-11-07)
- IBC 2021 1011.5.2: risers 7 in. maximum and 4 in. minimum, treads 11 in. minimum; exception for Group R-3, dwelling units in R-2 and accessory Group U: 7-3/4 in. and 10 in. Source: https://up.codes/viewer/colorado/ibc-2021/chapter/10/means-of-egress (read 2026-11-06)
- AWC DCA 6-2015: 7-3/4 in. maximum riser, 10 in. minimum tread, stairs at least 36 in. wide, an intermediate landing when the total stair height exceeds 12 ft 0 in. Source: https://web-media.awc.org/wp-content/uploads/2022/02/17210514/AWC-DCA62015-DeckGuide-1804.pdf (page 20 and Figure 27; read 2026-11-06)

## Sources

- [International Code Council: 2021 IRC, Chapter 3, Building Planning (R311.7 stairways; the official text)](https://codes.iccsafe.org/content/IRC2021P2/chapter-3-building-planning)
- [UpCodes: 2021 IRC Chapter 3 as adopted without amendments (R311.7.1 to R311.7.8, read in full)](https://up.codes/viewer/colorado/irc-2021/chapter/3/building-planning)
- [UpCodes: 2024 IRC Chapter 3 as adopted without amendments (Texas Windstorm Insurance Association; R318.7 stairways, R320.2 handrail height)](https://up.codes/viewer/texas/irc-2024/chapter/3/building-planning)
- [UpCodes: Residential Code of New York State 2025, Chapter 3 (R318.7.5.1 and R318.7.5.2 as amended)](https://up.codes/viewer/new_york/irc-2024/chapter/3/building-planning)
- [UpCodes: 2021 IBC Chapter 10, Means of Egress (1011.5.2 riser height and tread depth)](https://up.codes/viewer/colorado/ibc-2021/chapter/10/means-of-egress)
- [American Wood Council: DCA 6-2015, Prescriptive Residential Wood Deck Construction Guide (stairs, page 20)](https://web-media.awc.org/wp-content/uploads/2022/02/17210514/AWC-DCA62015-DeckGuide-1804.pdf)

## Notes

- Every cell was generated by running the klmlabs.app chart code, which uses the formulas of Construction Calculator 1.1.1 (an iPhone and iPad app by KLM Labs). Nothing was typed in by hand.
- A printed chart is a guide: measure on site, and check your local building code for stairs. Cities, counties and states adopt a code edition, often with amendments; this is a summary of the model code, not legal advice.
- License: CC BY 4.0. Credit: "KLM Labs, klmlabs.app".
