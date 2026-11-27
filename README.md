# M626 · Amplifiers

Ward-Beck Systems M626, 1971|4. Wiki page: [M626 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M626.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 0 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 0 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 0 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 2 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 1 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 2 |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1SmfmxTH09qAkytWzZflPotQb42NXmXbE/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1SmfmxTH09qAkytWzZflPotQb42NXmXbE" width="240" alt="1971 - M626 - DOC - WBSps.ca - 20210317 11X 17 Scans.png"></a><br><sub>1971|4 · DOC - WBSps.ca - 20210317 11X 17 Scans</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/14feC7ESAXIW1Nfq52P_FdLEN7aBycWPM/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=14feC7ESAXIW1Nfq52P_FdLEN7aBycWPM" width="240" alt="1971 - M626 - DOC - WLEES SBECIRE ANSLES.png"></a><br><sub>1971|4 · DOC - WLEES SBECIRE ANSLES</sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-7 | AC LINE | power | AC | medium |
| P1-16 | AC LINE | power | AC | medium |
| P2-1 | +B1 MEASURE | control_out | +B1 MEASURE + | medium |
| P2-5 | +B1 | strap |  | medium |
| P2-6 | +B1 OUT | out | +B1 OUT + | medium |
| P2-12 | CHASSIS GROUND | ground |  | medium |
| P2-14 | COMMON | ground |  | medium |
| P2-15 | COMMON | ground |  | medium |
| P2-16 | COMMON | ground |  | medium |

**Straps:** 5-6: P2-5 P2-6 · 14-15-16: P2-14 P2-15 P2-16

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M626.kicad_sym](KICAD/M626.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
