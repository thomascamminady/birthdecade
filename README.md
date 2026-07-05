# Birth decade explorer

Which birth decades dominate a country's population? Interactive explorer for
all 237 countries in the UN World Population Prospects 2024 — estimates
1950–2023 and medium-variant projections to 2100.

**Live:** https://thomascamminady.github.io/birthdecade/

Everything runs client-side: the site queries the raw parquet file
(`data/wpp.parquet`) with DuckDB-WASM via HTTP range requests, so only the
data for the countries you select is downloaded.

Made by [Thomas Camminady](https://camminady.dev).
