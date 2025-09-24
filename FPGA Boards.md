# FPGA Boards

Dieses Dokument listet einige FPGA Boards auf die ich gefunden habe und für meine Bachlor Arbeit in Frage kommen.

## FPGA Board Glossar

Ein LUT6 ist ein LUT mit 6 inputs.

Für die AMD / Xilinx:
- 1 Logic Cell ist ungefähr äquivalent zu 1 LUT4 + 1 flip-flop
- 1 System Logic Cell ist ein noch undefinierbarer Marketing Term

Für die AMD / Xilinx 7-Serie gilt:
- 1 Logic Slice entspricht 4 LUT6 (6-input LUT) und 8 flip-flops
- 1 CLB entspricht 2 Logic Slices (also 8 LUT6 und 16 flip-flops)
- 1 Logic Cell entspricht ungefähr 0.625 LUT6

Für die AMD / Xilinx UltraScale/UltraScale+ Serie:
- 1 Logic Slice entspricht 4 LUT6 (6-input LUT) und 8 flip-flops
- 1 CLB entspricht 1 Logic Slice
- 1 System Logic Cell entspricht ungefähr 0.459 LUT6

Quelle zur Einheiten Konvertierung: https://adaptivesupport.amd.com/s/question/0D52E00006hpm0xSAA/sysem-logic-cells

## Ausgewählte Anbieter

https://digilent.com/

- Der (meines wissens nach) bisherige der HHU bereits bekannte Anbieter für FPGAs

### Trenz Electronic

https://www.trenz-electronic.de/

- Bieten Rabatte für Akademische Institutionen an
- Offizieller Partner von AMD / Xilinx

### eBay

Auf eBay sind die scheinbar identischen Boards für die hälfte teilweise sogar ein zehntel des Preises verfügbar.
Die verschiedenen Verkäufer haben zwar sehr gute Bewertungen, jedoch ist unklar wie vertrauenswürdig diese sind.
Muss man gut aufpassen, vor allem da wir im Universitäts Kontekt handeln (Privat mögliche Option).

## FPGA Board Vorschläge

Alle Preisangaben ungefähr, Preise unterscheiden sich leicht zwischen Anbietern (± 10 %).
Die erste Preisangabe ist via Digilent, die mit Akademischen Rabatt ist von Trenz Electronic

### Basys 3

140 € (113 € für Akademische Institutionen)

FPGA Board: Artix-7 35T (XC7A35T)

https://digilent.com/reference/programmable-logic/basys-3/start

- Logic Cells: 33,280
- LUTs: 20,800
- Flip-Flops: 41,600
- Logic Slices: 5,200
- Das Board was die HHU bereits besitzt.

### Arty A7 (Variant: 100T)

255 € (201 € für Akademische Institutionen)

FPGA Board: Artix-7 100T (XC7A100T)

https://digilent.com/reference/programmable-logic/arty-a7/start

- Logic Cells: 101,440
- LUTs: 63,400
- Flip-Flops: 126,800
- Logic Slices: 15,850
- Gutes Upgrade gegenüber dem Basys 3 Board.

### Nexys A7

297 € (201 € für Akademische Institutionen)

FPGA Board: Artix-7 100T (XC7A100T)

https://digilent.com/reference/programmable-logic/nexys-a7/start

- Logic Cells: 101,440
- LUTs: 63,400
- Flip-Flops: 126,800
- Logic Slices: 15,850
- Ebenfalls kleines Updade gegenüber dem Basys 3 Board.
- Viele verschiedene Sensoren, Knöpfe, Anzeigen.
- Potentiell mehr Nachnutzungs möglichkeiten für zuküftige Projekte.
- Empholen für Lehre.
- Zwar mehr jedoch schlechtere Peripherien (e.g. kleinerer langsamerer Speicher).

### Nexys Video

468 € (290 € für Akademische Institutionen)

FPGA Board: Artix-7 200T (XC7A200T)

https://digilent.com/reference/programmable-logic/nexys-video/start

- Logic Cells: 215,360
- LUTs: 134,600
- Flip-Flops: 269,200
- Logic Slices: 33,650

### Genesys 2

936 € (606 € für Akademische Instutitionen)

FPGA Board: Kintex-7 325T (XC7K325T)

https://digilent.com/reference/programmable-logic/genesys-2/start

- Logic Cells: 326,080
- LUTs: 203,800
- Flip-Flops: 407,600
- Logic Slices: 50,950

## FPGA Board Vorschläge Extra

### Kria KV260

~ 242 € (theoretisch 212 € MSRP)

FPGA Board: ???

https://www.digikey.de/de/products/detail/amd/SK-KV260-G/13985269

- System Logic Cells: 256,000
- LUTs: 117,500
- Flip-Flops: 235,000
- Logic Slices: N/A
