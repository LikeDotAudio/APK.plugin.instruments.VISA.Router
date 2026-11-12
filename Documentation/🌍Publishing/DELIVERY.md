# Delivery — INSTRUMENT.Router

← [Publishing](INDEX.md)

A submodule of [APK.plugin.instruments.VISA](https://github.com/LikeDotAudio/APK.plugin.instruments.VISA) at `INSTRUMENT.Router/`, origin `https://github.com/LikeDotAudio/APK.plugin.instruments.VISA.Router.git`. It ships inside every image that bakes `INSTRUMENTS`; after a change here, regenerate (`python3 _komand/generate_device_apis.py`, `python3 _komand/family_sdk_docs.py` in the parent), commit here, bump the parent's pointer, and rebuild NODE.BareMetal, DISCOVERY.Engine and WEB.OsApi.

## Delivered 2026-11-11 – 2026-11-12

From this repository's own commits (the commit message is the record):

- ROAD-3667: Cards.json holds EDAC 2 — slot 7, from the workbook's 500 - EDAC 2 tab (`1a1188e`)
- ROAD-3667: Router.cad.json's terminals and capture points on the frame's slots (`24f6930`)
- tables: <Model>.scpi.json — the model's own SCPI tree for scpi_paths.py (`02326a6`)
- docs: SDK pages regenerated (ROAD-3683) (`2adba49`)

## Releases
- **Released `2.0.0`, tag `v2.0.0`** (2026-11-05, ROAD-3452, the owner's V2) — no SDK pin; every manifest says 2.0.0; GitHub release `v2.0.0`.
