# Overview

This is meant to facilitate turning the [Standard Navy Distribution
List](https://www.secnav.navy.mil/doni/SECNAV%20Manuals/Secretary%20of%20the%20Navy%20and%20Chief%20of%20Naval%20Operations%20Shore%20and%20Fleet%20Address%20Listings.xlsx)
into an accessible graph database.

Not much more for now, this is mostly for prototyping.

## Demo

See it in action at [this link](https://mpyne-navy.github.io/sndl-graph/). You
will need to download the Excel file at the SNDL link above to upload or
drag-and-drop into the page. For security reasons the Web page is designed to
avoid reaching out to any third-party site including the Navy's.

# Libraries

This uses:

* [SheetJS](https://github.com/SheetJS/sheetjs) (Apache 2.0 license),
* [LevelGraph](https://github.com/levelgraph/levelgraph) (MIT license), and
* [PaperCSS](https://www.getpapercss.com/) (ISC license)

The software itself is MIT-licensed.
