# Molly1

Molly1 is an 8-bit computer built in the style of front-panel computer designs of the 1970s. It utilizes an on-board ROM-based monitor with the ability to load, run, and store programs manually through a series toggle switches, or from secondary storage via an RS-232 bootloader. 

### Specs

- Rockwell W65C02 CPU enabling static/variable-clock-speed operation up to 1MHz. 
- 16-bit address bus, 8-bit data bus
- 32K ROM (28C256 - true capacity of ROM chip is not entirely addressable)
- 16K RAM (62256 - ditto)
- 1-2 65C22 VIAs (TBD depending on variety of inputs available + ability for them to be multiplexed/switched in and out in operation)
- Switchable fixed (1MHz) and "variable" (555-based) clocks

### Features

- Front panel LEDs: Power, D0-D7, A0-A15, CPU flags
- Front panel switches: D0-D7, A0-A15, Run/Stop, Single Step (?), Power On-Off, Reset, Deposit/Store
- Power - 5V 3A wall wart
- Chassis - Wood w/ dark brown stain (e.g. mahogany), blue/green/white front panel elements
