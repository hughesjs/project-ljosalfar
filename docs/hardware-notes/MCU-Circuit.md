# Hardware Choice

## MCU

The [STM32F030](https://jlcpcb.com/partdetail/Stmicroelectronics-STM32F030C8T6/C23922) is the chip of choice (primarily because it's a basic part at JLCPCB). 

### Datasheet 
![[STM32F030C8T6-Datasheet.pdf]]

### User Manual
![[STM32Fxxx-Reference-Manual.pdf]]

### Application Note
![[STM32F0x1-Application-Note.pdf]]

# Caps

| Capacity (F) | Part No | JLPCB Link |
|----|----|----|
| 100n | CL05B104KB54PNC | https://jlcpcb.com/partdetail/291005-CL05B104KB54PNC/C307331 |
| 10pF | CL05C100JB5NNNC | https://jlcpcb.com/partdetail/33914-CL05C100JB5NNNC/C32949 |

## Oscillators

### Main Clock

8MHz [X49SM8MSD2SC](https://jlcpcb.com/partdetail/YangxingTech-X49SM8MSD2SC/C12674) Crystal Oscillator should do. Can be ramped up to a 32MHz crystal if we need to.

![[8MHz-Crystal-Oscillator-Datasheet.pdf]]


# Pin Assignments

# Power Supply

VDD is standard power. VDDA is analogue power. We can just tie these together.

VSS is ground.

`2.0 < VDD < 3.6`

`VDDA == VDD`



PA0-12 + PA 15

PA 13 14