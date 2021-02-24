# mducngCV

https://www.overleaf.com/project/5ff42973812625c230bac28b

On-cell/In-cell active pen supported touchscreen controller for large screen device.

ASIC/ FPGA

Active pen supported touchscreen controller - Evaluation board verification 
- EVB setup: FPGA Altera D10-standard, extra MCU(Andes D10 core), and STM32F401 board.
- Capacitance sensing sensor design, MUX controller with STM32F429ZI, NUCLEO-L552ZE. 
- ADC ADS5271 with IP cores LVDS bus, SPI bus controller interface
- SRAM memory, FIFO memory controller
- to detect and synchonize active pen signal
- to reconstruct and process raw signal of Active pen using DSP algorithms
- to distinguish the Tip Pressure from 256 levels
- to seperate/ extract tip/tilt information for each symbol
