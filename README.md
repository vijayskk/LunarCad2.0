# LunarCad 2.0 Schedule

## Chapter 0 - Welcome
- Basic Welcome procedures
- What is LunarCad
- Why there is a 2.0
- Mission briefing.
## Chapter 1 - Basics
- Basics about electronics components such as:
    - Resistor
    - Capacitor
    - Diode
    - LEDs and Switches
    - Crystal
    - ICs in general
- Form factors and packaging of components:
    - SMD
    - Thorough Hole
- Some good practices, dos and don'ts.:
    - Power Supply
    - Polarity
    - Troubleshooting
    - 
## Chapter 2 - Knowing PCBs
- Basics about PCBs such as:
    - Why we use PCBs
    - Different layers of PCB (Important)
    - Manufacturing methods and costs
    - Best Manufacturing options
- TO BE FILLED
## Chapter 3 - Welcome to EasyEDA
- Installation and signup.
- Knowing the UI
- Selection of components. (TODO: we should make a list of the correct component codes in EasyEDA)
- A small LDR Circuit designing. By doing we will teach:
    - How to search and select components.
    - How to wire the connections and make annotations
    - How do we convert it into pcb
    - How to place components properly
    - How to route the connections. Both manual and auto routing.
    - How to export the design for etching (Important)
## Chapter 4 - Knowing Atmega328p and Arduino.
- Basics of Atmega328p such as:
    - Specifications 
    - Pinouts
    - Boot cycle and program execution (boot loader working)
    - Usage of pins such as:
        | Pin Category | Important Pins           | Function                          |
        | ------------ | ------------------------ | --------------------------------- |
        | Power        | VCC, AVCC, GND           | Provides digital & analog supply  |
        | Clock        | PB6 (XTAL1), PB7 (XTAL2) | Connect to crystal                |
        | Reset        | PC6 (RESET#)             | Connect to reset switch & pull-up |
        | Serial       | PD0 (RXD), PD1 (TXD)     | For uploading programs            |
        | I/O          | All remaining pins       | Digital & analog functions        |
- Explain the working of each circuits as in the schematics [here](SCH_Schematic1_2025-11-28.pdf)

## Chapter 5 - Designing Arduino in EasyEda
- Searching and selection of components.
- Wiring up the circuit.
- Converting it to pcb and placing components.
- Anyone can use their brains and come up with an optimal design. But for reference see this placement diagram [here](PCB_PCB1_2025-11-28.pdf).
- Exporting the only needed layers for etching.
## Chapter 6 - Hand on Etching
- Explain the chemistry behind.
- Familiarise with all the materials and tools such as:
    - Copper clad
    - Feric Chloride
- Hand on etching:
    - Iron for 5 min for toner transfer
    - Take 200ml water for half of the powder.
    - Wait 15 minutes.
    - clean the toner.
    - Drill holes with 0.3mm drill bits.
## Chapter 7 - Soldering
- Component placement.
- Explain best soldering practices.
## Chapter 8 - Preparing the new board for first program
- Burning the bootloader using Arduino as ISP.
- Programming the new Arduino with CP2102 Usb-Serial.
- Running the first program.
## Bonus Chapter
- Some programming basics.