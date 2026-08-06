<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ffffff,100:ffffff&height=230&section=header&text=ATLAS&fontSize=80&fontColor=111111&animation=fadeIn&fontAlignY=34&desc=All%20The%20Locations%20of%20All%20Servers&descSize=17&descAlignY=54"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=808080&center=true&vCenter=true&multiline=true&repeat=true&width=950&height=80&lines=All+The+Locations+of+All+Servers.;18%2C110+facilities+%C2%B7+116+countries+%C2%B7+4%2C181+operators;The+internet+is+not+a+cloud.+It+is+buildings.)](https://git.io/typing-svg)

[![Facilities](https://img.shields.io/badge/FACILITIES-18%2C110-000000?style=for-the-badge&labelColor=000000)](#)
[![Countries](https://img.shields.io/badge/COUNTRIES-116-2E2E2E?style=for-the-badge&labelColor=000000)](#)
[![Operators](https://img.shields.io/badge/OPERATORS-4%2C181-4A4A4A?style=for-the-badge&labelColor=000000)](#)
[![Formats](https://img.shields.io/badge/FORMATS-12-6E6E6E?style=for-the-badge&labelColor=000000)](#)
[![License](https://img.shields.io/badge/LICENSE-ATTRIBUTION-808080?style=for-the-badge&labelColor=000000)](LICENSE)

**The largest open data center location dataset on the internet.**

Free to use for research, publications, and products. Credit required.

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:e3e3e3,50:c9c9c9,100:e3e3e3&height=3&section=header"/>

<p align="center">
  <img src="atlas.jpg" alt="ATLAS Globe" width="500">
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Ringmast4r-Global-Data-Center-Map&label=Visitors&color=808080&style=flat-square" alt="Visitors">
</p>

<p align="center">
  <a href="https://www.buymeacoffee.com/ringmast4r" target="_blank">
    <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ringmast4r-000000?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" alt="Buy Me A Coffee">
  </a>
</p>

<h1 align="center">ATLAS</h1>
<h3 align="center"><b>A</b>ll <b>T</b>he <b>L</b>ocations of <b>A</b>ll <b>S</b>ervers</h3>

<p align="center"><i>Map every data center on Earth.</i></p>

<p align="center">
  <a href="https://data-center-map.com"><b>View Live Map</b></a>
</p>

---

<h2 align="center">At a Glance</h2>

<p align="center">

```
+------------------+---------+
| Data Centers     | 18,110  |
| Countries        |    116  |
| Operators        |  4,181  |
| With GPS Coords  |  6,131  |
| Raw (Pre-Dedup)  | 25,757  |
+------------------+---------+
```

</p>

<h2 align="center">Top 15 Countries</h2>

<p align="center">

```
United States     ████████████████████████████████████  8,818
United Kingdom    ███                                     747
Germany           ██                                      584
France            ██                                      558
China             ██                                      548
Netherlands       ██                                      444
Canada            █                                       415
Australia         █                                       396
India             █                                       342
Brazil            █                                       298
Italy             █                                       250
Japan             █                                       236
Spain             █                                       221
Indonesia                                                 193
Russia                                                    180
```

</p>

<h2 align="center">Top 10 Operators</h2>

<p align="center">

```
Amazon AWS            ████████████████████████████████████  533
Equinix               ████████████████████████████████      482
Lumen                 ███████████████████████████           403
China Telecom         █████████████████████                 316
Zenlayer              ████████████████████                  309
Digital Realty        ████████████████████                  299
DataBank              ██████████████                        217
Google                █████████████                         205
Microsoft             ████████████                          188
Digital Realty Trust  ███████████                           164
```

</p>

---

<h2 align="center">Downloads</h2>

<p align="center">All 18,110 facilities in every common format:</p>

<div align="center">

| File | Format | Size | Records | Notes |
|------|--------|------|---------|-------|
| [`datacenters.csv`](datacenters.csv) | CSV | 1.7 MB | 18,110 | Excel/Google Sheets compatible |
| [`datacenters.xlsx`](datacenters.xlsx) | Excel | 996 KB | 18,110 | Bold headers, auto-width columns |
| [`datacenters.json`](datacenters.json) | JSON | 4.8 MB | 18,110 | Full dataset with coordinates |
| [`datacenters.geojson`](datacenters.geojson) | GeoJSON | 1.6 MB | 6,131 | Import into QGIS, Mapbox, ArcGIS |
| [`datacenters.kml`](datacenters.kml) | KML | 1.1 MB | 6,131 | Google Earth / Google Maps |
| [`datacenters.tsv`](datacenters.tsv) | TSV | 1.7 MB | 18,110 | Tab-separated for scripting |
| [`datacenters.xml`](datacenters.xml) | XML | 4.5 MB | 18,110 | Structured markup |
| [`datacenters.db`](datacenters.db) | SQLite | 2.0 MB | 18,110 | Query with SQL, no server needed |
| [`datacenters.parquet`](datacenters.parquet) | Parquet | 826 KB | 18,110 | Columnar format for analytics |
| [`datacenters.sql`](datacenters.sql) | SQL | 3.8 MB | 18,110 | CREATE TABLE + INSERT statements |
| [`datacenters.yaml`](datacenters.yaml) | YAML | 3.1 MB | 18,110 | Human-readable structured data |
| [`datacenters-table.md`](datacenters-table.md) | Markdown | 1.4 MB | 18,110 | Browse the full list on GitHub |
| [`datacenters_raw.json`](datacenters_raw.json) | JSON (raw) | 5.1 MB | 25,757 | Full raw pre-dedup collection for auditing |

</div>

<p align="center"><i>GeoJSON and KML contain the 6,131 facilities (33.9%) that have verified GPS coordinates.</i></p>
<p align="center"><i>The main <code>datacenters.json</code> is deduplicated. The <code>_raw</code> version is the pre-dedup collection for transparency.</i></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:e3e3e3,50:c9c9c9,100:e3e3e3&height=3&section=header"/>

<h2 align="center">License</h2>

This dataset was previously **All Rights Reserved**. Because of the number of
requests to use it, that restriction has been lifted.

You may use, copy, publish, and build on this data - research papers, white
papers, articles, visualizations, internal tools, commercial products - on one
condition: **credit it.**

```
Data centers (c) Ringmast4r - Global-Data-Center-Map
https://github.com/Ringmast4r/Global-Data-Center-Map
```

You do not need to ask permission. You do not owe me an email. But if you are
building something with it, I would genuinely like to hear what - open an issue
and tell me. I am curious.

See [LICENSE](LICENSE) for the full terms, including a note on coordinate
precision you should read before relying on this for anything serious.


<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ffffff,100:ffffff&height=140&section=footer"/>
