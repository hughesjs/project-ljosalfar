# Hardware Choice

## MCU

The [STM32F072CBT6](https://jlcpcb.com/partdetail/Stmicroelectronics-STM32F072CBT6/C81720) is the chip of choice as the smallest STM32 with USB support.

### Datasheet 
![[STM32F072CBT6-Datasheet.pdf]]

### User Manual
![[STM32Fxxx-Reference-Manual.pdf]]

### Application Note
![[STM32F0x1-Application-Note.pdf]]

# Caps

| Capacity (F) | Part No | JLPCB Link |
|----|----|----|
| 100n | CL05B104KB54PNC | https://jlcpcb.com/partdetail/291005-CL05B104KB54PNC/C307331 |
| 10pF | CL05C100JB5NNNC | https://jlcpcb.com/partdetail/33914-CL05C100JB5NNNC/C32949 |
| 1uF | CL21B105KBFNNNE | https://jlcpcb.com/partdetail/29074-CL21B105KBFNNNE/C28323 |
| 12pF | 0402CG120J500NT | https://jlcpcb.com/partdetail/1899-0402CG120J500NT/C1547 | 
| 10nF | CL05B103KB5NNNC | https://jlcpcb.com/partdetail/15869-CL05B103KB5NNNC/C15195 |
| 4.7uF  | CL21A475KAQNNNE | https://jlcpcb.com/partdetail/2131-CL21A475KAQNNNE/C1779 | 
| 4.7nF | 0402B472K500NT| https://jlcpcb.com/partdetail/1890-0402B472K500NT/C1538 |

Some sage advice:

![[decoupling-cap-advice.png]]

## Oscillators

### Main Clock

32 MHz Crystal Oscillator [X322532MOB4SI](https://jlcpcb.com/partdetail/YangxingTech-X322532MOB4SI/C9009)

![[32MHz-Crystal-Oscillator-Datasheet.pdf]]

# Pin Assignments

# Power Supply

VDD is standard power. VDDA is analogue power. We can just tie these together.

VSS is ground.

`2.0 < VDD < 3.6`

`VDDA == VDD`



PA0-12 + PA 15

PA 13 14