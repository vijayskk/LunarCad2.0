# LunarCad 2.0 Schedule

## Things we have to give

* Provide the components and materials
* Provide the list of component codes in EasyEDA
* Provide all the schematics and other files
* Provide the suitable drivers for the CP2102

## Chapter 0 - Welcome

* Basic welcome procedures
* What is LunarCad
* Why there is a 2.0
* Mission briefing

## Chapter 1 - Basics

* Basics about electronic components such as:

  * Resistor
  * Capacitor
  * Diode
  * LEDs and switches
  * Crystal
  * ICs in general
* Form factors and packaging of components:

  * SMD
  * Through Hole
* Some good practices, dos and don'ts:

  * Power supply
  * Polarity
  * Troubleshooting

## Chapter 2 - Knowing PCBs

* Basics about PCBs such as:

  * Why we use PCBs
  * Different layers of a PCB (Important)
  * Manufacturing methods and costs
  * Best manufacturing options
* TO BE FILLED

## Chapter 3 - Welcome to EasyEDA

* Installation and signup
* Knowing the UI
* Selection of components (TODO: we should make a list of the correct component codes in EasyEDA)
* A small LDR circuit design. By doing this we will teach:

  * How to search and select components
  * How to wire the connections and make annotations
  * How to convert it into a PCB
  * How to place components properly
  * How to route the connections, both manual and auto-routing
  * How to export the design for etching (Important)

## Chapter 4 - Knowing Atmega328p and Arduino

* Basics of Atmega328p such as:

  * Specifications
  * Pinouts
  * Boot cycle and program execution (bootloader working)
  * Usage of pins such as:

    | Pin Category | Important Pins           | Function                          |
    | ------------ | ------------------------ | --------------------------------- |
    | Power        | VCC, AVCC, GND           | Provides digital & analog supply  |
    | Clock        | PB6 (XTAL1), PB7 (XTAL2) | Connect to crystal                |
    | Reset        | PC6 (RESET#)             | Connect to reset switch & pull-up |
    | Serial       | PD0 (RXD), PD1 (TXD)     | For uploading programs            |
    | I/O          | All remaining pins       | Digital & analog functions        |
* Explain the working of each circuit as in the schematics [here](SCH_Schematic1_2025-11-28.pdf)

## Chapter 5 - Designing Arduino in EasyEDA

* Searching and selecting components
* Wiring up the circuit
* Converting it to PCB and placing components
* Anyone can use their brains and come up with an optimal design. But for reference, see this placement diagram [here](PCB_PCB1_2025-11-28.pdf)
* Exporting only the needed layers for etching

## Chapter 6 - Hands-on Etching

* Explain the chemistry behind it
* Familiarise with all the materials and tools such as:

  * Copper clad
  * Ferric chloride
* Hands-on etching:

  * Iron for 5 minutes for toner transfer
  * Take 200 ml water for half of the powder
  * Wait 15 minutes
  * Clean the toner
  * Drill holes with 0.3 mm drill bits

## Chapter 7 - Soldering

* Component placement
* Explain best soldering practices

## Chapter 8 - Preparing the New Board for the First Program

* Burning the bootloader using Arduino as ISP
* Programming the new Arduino with CP2102 USB-Serial. Driver is [Here](pololu-cp2102-windows-220616.zip)
* Running the first program

## Bonus Chapter

* Some programming basics
