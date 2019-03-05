
Microcontroller Workshop
========================

In preparation for the workshop, please follow the [installation guide](INSTALL.md).
You should be able to compile a modm project for ARM (Cortex-M3). See
`examples/blink`.

## FR
===
* virtual machine mit USB Weiterleitung
* oder Arduino

## Bootloader
* ist schon geladen
* 8 kB
* Jumpers steuern das Verhalten des Bootloaders
* rechten nach oben, linken nach unten
* B0- B1+ ließt ständig Informationen von dem USB
* B0- B1- 
** Warten kurz nach dem Reset (Change für das Laden das Programm USB)
** Danach schon geladener Code angezeigt


```makefile
make prepare
make build
```
reset auf dem chip

examples/display

## Für Windows
- (blue pill  and black pill) - glei
 [black pill] (https://wiki.stm32duino.com/index.php?title=Black_Pill)
- [Blue Pill Tool Chain für arduino ](https://wiki.stm32duino.com/index.php?title=Blue_Pill)
- [data sheet] (https://github.com/dergraaf/microcontroller-workshop-2019/tree/master/doc)
- STM32F103x8

## Hands on
- c:\Users\Filip\Source\Repos\microcontroller-workshop-2019\examples\display\main.cpp
- Programm ungefähr 16 kB
- space invaders