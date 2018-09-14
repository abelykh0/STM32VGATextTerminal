STM32VGATextTerminal
====================

Text terminal on the microcontroller STM32F103x. The project is intended
to output text information to monitors with a VGA interface. Supported
resolution of 640x480 in monochrome, the font size is 8x16, which allows
for 80x30 characters.

Link: https://github.com/vasyaod/STM32VGATextTerminal

Author: vasyaod (vasyaod@mail.ru)

## Changes compared to the original project

The project is modified to support STM32F103C8, which doesn't have TIM5. Also,
it is changed to build under Atollic TrueStudio 9.0.
