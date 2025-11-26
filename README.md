# LED Key PCB (KiCad)

A simple LED Key PCB designed in KiCad. The board uses a through-hole LED, a single through-hole current-limiting resistor, and a momentary switch footprint. Connection pads are clearly labeled, and the overall layout is clean and easy to assemble.

## Features
- Through-hole LED and resistor  
- Momentary switch footprint  
- Clean, minimal KiCad layout  
- Straightforward power and signal pads  

## Bill of Materials (BOM)

A full, BOM is available here:  
**https://docs.google.com/spreadsheets/d/1AzciDIwuh-wBaT5EASdSV9_-SiR-sQ5o8lEvPlcvOwY/edit?usp=sharing**

| # | Reference | DNP | Part Name        | Manufacturer                                   | MPN                     | Qty | Footprint | Notes            |
|---|-----------|-----|------------------|-------------------------------------------------|--------------------------|-----|-----------|------------------|
| 1 | SW1A      | No  | Tactile Button   | Omron Electronics Inc-EMC Div                  | B3F-1000                | 1   | THT       | —                |
| 2 | BT1       | No  | Battery Holder   | Keystone Electronics                           | 1058                    | 1   | SMD       | Coin Cell 2032   |
| 3 | R1        | No  | Resistor         | Vishay Beyschlag/Draloric/BC Components        | MBA0204VE1000BC100      | 1   | THT       | —                |
| 4 | D1        | No  | LED              | Kingbright                                     | WP56BID                 | 1   | THT       | Red              |
| 5 | N/A       | N/A | PCB              | PCBWay                                         | N/A                     | 5   | N/A       | —                |

## Files Included
- Schematic  
- PCB layout  
- Gerber files

## How It Works
The LED is powered through a single current-limiting resistor, and the momentary switch provides the primary input. External power, ground, and signal lines connect through the labeled pads.

## License
This project is licensed under the **MIT License**.
