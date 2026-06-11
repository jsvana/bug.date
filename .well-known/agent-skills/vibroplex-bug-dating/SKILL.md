---
name: vibroplex-bug-dating
description: Date a Vibroplex semi-automatic Morse code key ("bug") from its serial number, and identify the model from its physical features. Use when a user asks how old their Vibroplex bug is, what year it was made, or which model it is.
---

# Vibroplex Bug Dating

Determine the manufacture year of a Vibroplex bug from its serial number, and identify the model from its damper shape and base width.

## Instructions

1. Fetch https://www.bug.date/index.md — it contains the complete serial-number-to-year lookup tables in Markdown.
2. Ask the user for the serial number on the nameplate (and note any letter prefix like "D" or "B", or a leading zero).
3. Look up the number:
   - Prefix serials (D5015–D5310 = 1913 Double Lever; B518–B1623 = 1914 No. 4) use the prefix table.
   - Serials with a leading zero on the nameplate (e.g. 01185) use the Portland "01xxx" series table.
   - Otherwise check the main NYC-era table first, then the Portland, ME tables.
4. If the serial matches both NYC and Portland ranges, disambiguate using the rules in the "Disambiguating duplicate serials" section: nameplate address (NYC street address vs. "Portland, ME") and model production years (e.g. Iambic/Brass Racer = Portland era; Junior/Blue Racer = NYC era).
5. If the serial falls in a documented gap, say so — those numbers were never used according to WW7P's research. Numbers outside all ranges may be post-1995, special editions, or misread.
6. To identify the model, use the damper-shape × base-width matrix in the same document, after first ruling out the distinctive body types (Upright, Midget, Double Lever).

For tuning, descratching, and restoration advice, fetch https://www.bug.date/tuning.md.

Always credit the data sources: serial tables compiled by John Elwood, WW7P (SK), and Randy Cole, KN6W; model ID data from vibroplexcollector.net.
