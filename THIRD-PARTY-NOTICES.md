# Third-party notices

Everything in this repository was written for SAME Post Tools, except the items below. The pages load nothing from other servers: no scripts, fonts, styles, or images.

| Item | Used in | Source | License |
|---|---|---|---|
| jsPDF 4.2.1 | Events finder, Save as PDF | Copyright (c) 2010-2021 James Hall, (c) 2015-2021 yWorks GmbH | MIT (`licenses/jspdf-LICENSE.txt`; the notice is also inside the inlined library) |
| PDF.js 6.5.438 (legacy build) | Membership numbers, reading a National report you open | Copyright Mozilla Foundation and contributors | Apache License 2.0 (`licenses/pdfjs-LICENSE.txt`; the notice is also inside the inlined library). Run with script evaluation turned off and no font loading |
| Atkinson Hyperlegible, Regular and Bold, Latin subset | Optional font in Options (embedded in the events finder and membership numbers; `assets/fonts/` for the home page) | Copyright 2020 Braille Institute of America, Inc., via the Fontsource Latin subset | SIL Open Font License 1.1 (`licenses/OFL.txt`) |
| U.S. state, Alaska, Hawaii, and Puerto Rico outlines | Events finder map and member map | us-atlas 3.0.1 (Copyright 2013-2019 Michael Bostock), repackaging the U.S. Census Bureau's 2017 cartographic boundary files (public domain) | ISC (notice below) |
| Map projection | Events finder map | Written for this project; checked against d3-geo's geoAlbersUsa (Copyright 2010-2026 Mike Bostock) | ISC (notice below), as a courtesy |
| ZIP code locations and metro and micro areas | Member roster report, member map | U.S. Census Bureau: 2023 ZCTA Gazetteer, 2020 ZCTA-to-county relationship file, July 2023 CBSA delineation | Public domain (U.S. government work) |
| U.S. cities and towns of 15,000 people or more (names, states, locations) | Events finder, Post finder | GeoNames (https://www.geonames.org/), via the geonamescache package's data files; extracted 2026-11-28 | Creative Commons Attribution 4.0 (https://creativecommons.org/licenses/by/4.0/); credited in the page |
| SAME name and colors | All pages | Society of American Military Engineers | Belong to SAME. No SAME logo is used |
| Membership counts | Membership numbers | SAME National, Post Membership Stats, public monthly reports in the Post Resource Center on same.org | SAME National's figures, credited in the page; not covered by this repository's license |
| Event listings | Events finder | Public event listings (same.org and Post sites) and the Industry Days list compiled by Bobbi Jo Lang | Facts and links, credited in the page; not covered by this repository's license |

## ISC license

us-atlas: Copyright 2013-2019 Michael Bostock. d3-geo: Copyright 2010-2026 Mike Bostock. topojson-client and topojson-simplify (used only to build the map file): Copyright 2012-2019 Michael Bostock.

> Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.
>
> THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
