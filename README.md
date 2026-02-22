# STM32-USBb

STM32-USBb is an **experimental PCB** based on an **STM32 microcontroller**, designed for research and prototyping purposes.

This board is part of the **Raptor project** by [Infinite](https://github.com/infiniteHQ).

> [!IMPORTANT]
> This PCB is **not production-ready**.  
> It is purely experimental and intended only for early development and future work within the Infinite project.

## Preview

![Preview](assets/preview.png)

## PCB

![PCB](assets/pcb.png)

## Components list (ref & role)

- **U1** : STM32 (STM32F103C8T6) microcontroller (main MCU)
- **U2** : 3.3 V linear voltage regulator

- **Y3** : 16 MHz external crystal (MCU clock)

- **J1, J2, J3** : Pin headers (GPIO / debug / expansion)
- **J4** : USB Micro-B connector (power + USB data)

- **SW1** : Power / mode selection switch

- **D1** : Status LED

- **FB1** : Ferrite bead (power supply noise filtering)

- **R1** : USB pull-up resistor
- **R2** : MCU reset / configuration pull resistor
- **R3, R4, R5** : Current limiting / configuration resistors

- **C1, C2** : Bulk input/output decoupling capacitors
- **C3, C4, C5, C6, C11** : MCU decoupling capacitors
- **C7** : Local bulk decoupling capacitor
- **C8, C9, C10** : Power rail filtering capacitors
- **C12, C13** : Crystal load capacitors