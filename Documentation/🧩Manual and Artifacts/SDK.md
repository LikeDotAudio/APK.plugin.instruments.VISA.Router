# SDK — INSTRUMENT.Router

Every Router model this library drives, and how to drive it. Each model answers the same five verbs over HTTP (its own port), WebSocket, a Unix socket and the bus; one page per model below lists its routes and every command.

← [Manual and Artifacts](INDEX.md)

| Verb | What it does |
|---|---|
| `get` | reads one value |
| `set` | writes one value |
| `nab` | reads more than one thing (observation, telemetry) |
| `rig` | configures several arguments at once |
| `do` | executes an action; takes no value |

| Model | Maker | get | set | nab | rig | do | Port |
|---|---|---:|---:|---:|---:|---:|---:|
| [3235](SDK/3235.md) | HP / Agilent / Keysight | 2 | 2 | 2 | 0 | 34 | 15100 |
| [3235A](SDK/3235A.md) | HP / Agilent / Keysight | 2 | 2 | 2 | 0 | 34 | 15101 |
