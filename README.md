# STM32 RPM Meter

STM32 NUCLEO-L073RZ pagrindu realizuota rato apsukų greičio matavimo sistema.

## Naudojami komponentai

- STM32 NUCLEO-L073RZ
- Herkoninis jutiklis
- Magnetas
- SSD1306 OLED ekranas
- UART / ST-LINK Virtual COM ryšys su PC

## Veikimo principas

Sistema fiksuoja magneto praėjimus pro herkoną, apskaičiuoja rato apsukų greitį, rezultatą rodo OLED ekrane ir perduoda į kompiuterį per UART.