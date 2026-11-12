<!-- BEGIN GENERATED — apkaudio-komand build-trees -->

# Router/3235 — command tree

Generated from the `.komand` table by `apkaudio-komand build-trees`. Edit the table, not this file.

**38 commands** — SET 2 · RIG 0 · NAB 2 · DO 34 · 2 unverified (5%)

`SET` one argument · `RIG` several applied together · `NAB` a query · `DO` a parameterless action. **†** marks a command swept out of a manual and never sent to the instrument.

## Tree

- `CLOSE` — **SET** `Close_Channels` · `<channel_list>` · args: `channel_list` · string
- `OPEN` — **SET** `Open_Channels` · `<channel_list>` · args: `channel_list` · string
- `CLOSE?` — **NAB** `Query_Channel_State` · `<chan>` · per-instance: `chan` · → 1 value · †
- `ID?` — **NAB** `Query_Slot_ID` · `<slot>` · per-instance: `slot` · → 1 value · †
- `CRESET` — **DO** `Card_Reset` · `<slot>` · per-instance: `slot`
- `CLR` — **DO** `Clear_State`
- `CLOSE` — **DO** `Close_All` · `000-999`<br>Close every relay in the frame — everything connected to everything.
- `CLOSE` — **DO** `Close_Card_0` · `000-099`<br>Coax Left: close every relay on slot 0
- `CLOSE` — **DO** `Close_Card_1` · `100-199`<br>Coax Right: close every relay on slot 1
- `CLOSE` — **DO** `Close_Card_6` · `600-699`<br>EDAC 1: close every relay on slot 6
- `CLOSE` — **DO** `Close_Card_7` · `700-799`<br>EDAC 2: close every relay on slot 7
- `CLOSE` — **DO** `Close_Card_8` · `800-899`<br>EDAC 3: close every relay on slot 8
- `CLOSE` — **DO** `Close_Card_9` · `900-999`<br>Aux: close every relay on slot 9
- `CLOSE` — **DO** `Connect_Card_6_AB0` · `690`<br>EDAC 1: connect bank 0 outputs to AB0 (LEFT SEND)
- `CLOSE` — **DO** `Connect_Card_6_AB1` · `691`<br>EDAC 1: connect bank 1 inputs to AB1 (LEFT RETURN)
- `CLOSE` — **DO** `Connect_Card_6_AB2` · `692`<br>EDAC 1: connect bank 2 outputs to AB2 (RIGHT SEND)
- `CLOSE` — **DO** `Connect_Card_6_AB3` · `693`<br>EDAC 1: connect bank 3 inputs to AB3 (RIGHT RETURN)
- `CLOSE` — **DO** `Connect_Card_7_AB0` · `790`<br>EDAC 2: connect bank 0 outputs to AB0 (LEFT SEND)
- `CLOSE` — **DO** `Connect_Card_7_AB1` · `791`<br>EDAC 2: connect bank 1 inputs to AB1 (LEFT RETURN)
- `CLOSE` — **DO** `Connect_Card_7_AB2` · `792`<br>EDAC 2: connect bank 2 outputs to AB2 (RIGHT SEND)
- `CLOSE` — **DO** `Connect_Card_7_AB3` · `793`<br>EDAC 2: connect bank 3 inputs to AB3 (RIGHT RETURN)
- `CLOSE` — **DO** `Connect_Card_8_AB0` · `890`<br>EDAC 3: connect bank 0 outputs to AB0 (LEFT SEND)
- `CLOSE` — **DO** `Connect_Card_8_AB1` · `891`<br>EDAC 3: connect bank 1 inputs to AB1 (LEFT RETURN)
- `CLOSE` — **DO** `Connect_Card_8_AB2` · `892`<br>EDAC 3: connect bank 2 outputs to AB2 (RIGHT SEND)
- `CLOSE` — **DO** `Connect_Card_8_AB3` · `893`<br>EDAC 3: connect bank 3 inputs to AB3 (RIGHT RETURN)
- `CLOSE` — **DO** `Connect_Card_9_AB0` · `990`<br>Aux: connect bank 0 outputs to AB0 (LEFT SEND)
- `CLOSE` — **DO** `Connect_Card_9_AB1` · `991`<br>Aux: connect bank 1 inputs to AB1 (LEFT RETURN)
- `CLOSE` — **DO** `Connect_Card_9_AB2` · `992`<br>Aux: connect bank 2 outputs to AB2 (RIGHT SEND)
- `CLOSE` — **DO** `Connect_Card_9_AB3` · `993`<br>Aux: connect bank 3 inputs to AB3 (RIGHT RETURN)
- `OPEN` — **DO** `Open_All` · `000-999`<br>Open every relay in the frame — nothing connected to anything.
- `OPEN` — **DO** `Open_Card_0` · `000-099`<br>Coax Left: open every relay on slot 0
- `OPEN` — **DO** `Open_Card_1` · `100-199`<br>Coax Right: open every relay on slot 1
- `OPEN` — **DO** `Open_Card_6` · `600-699`<br>EDAC 1: open every relay on slot 6
- `OPEN` — **DO** `Open_Card_7` · `700-799`<br>EDAC 2: open every relay on slot 7
- `OPEN` — **DO** `Open_Card_8` · `800-899`<br>EDAC 3: open every relay on slot 8
- `OPEN` — **DO** `Open_Card_9` · `900-999`<br>Aux: open every relay on slot 9
- `RESET` — **DO** `Reset_Device`<br>Reset System
- `SELECT` — **DO** `Select_Channel` · `<chan>` · per-instance: `chan`

<!-- END GENERATED -->
