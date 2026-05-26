# STM32G4_SOM
STM32G473 SYSTEM ON MODULE

This project is a straightforward STM32 based system on module for use in my various projects.

Features:
- MCU: STM32G473VET6
- QSPI onboard flash memory
- 32.678kHz and 8MHz MEMS oscillators
- USB interface
- Power path selection from USB 5V and 5V from whatever motherboard this connects to.
- 5V to 3.3V LDO
- 2x onboard LEDs
- 1x on board temperature sensor

Peripherals broken out via mezzanine connector:
- Two SPI ports, one that can be SPI or I2S
- One Encoder
- Two I2C ports
- One LPUART
- Two single ended ADC channels
- One Differnetial ADC channel
- One FMC port configured for Motorola 8080 16-bit display driving
- 9 GPIOs

  <img width="1338" height="812" alt="image" src="https://github.com/user-attachments/assets/89faf4ce-c091-440c-87ca-e12dab0b49cc" />
