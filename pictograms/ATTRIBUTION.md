# Pictogram Attribution

The pictograms in this folder are from the **ARASAAC** (Aragonese Portal of Augmentative and Alternative Communication) symbol set.

- **Source:** https://arasaac.org
- **Author:** Sergio Palao
- **Originator:** Government of Aragón (Spain)
- **License:** Creative Commons BY-NC-SA 4.0
  - https://creativecommons.org/licenses/by-nc-sa/4.0/

Pictograms are distributed for non-commercial use with attribution and share-alike. The Connectus AAC MVP is a free, non-commercial educational/communication tool and credits ARASAAC visibly in the app's About section and on this page.

## Pictogram mapping

Each PNG file in this directory corresponds to an AAC "kind" used by `tileVisuals` in the app. Filename is the kind key; the ARASAAC pictogram ID used is recorded in `pictograms/index.json`.

Pictograms downloaded at 500x500 resolution via the public ARASAAC API:
`https://api.arasaac.org/api/pictograms/{id}?resolution=500`

Distinct pictograms are used for `hello` (ID 6522) and `goodbye` (ID 6028) so the two
greetings render with visually different symbols, and `all_done` (ID 28429), `stop`
(ID 8289), `go` (ID 36448), and `want` (ID 31141) were chosen for clearer, more
intuitive iconography (an actual stop sign, a green-lit traffic light, two crossed
hands signalling "finished", and a hand-only reach).

This project does NOT use proprietary symbol sets (Boardmaker/PCS, SymbolStix, Widgit) and makes no claim of exact equivalence to them.
