STM32VGATextTerminal
====================

Text terminal on the microcontroller STM32F103x. The project is intended
to output text information to monitors with a VGA interface. Supported
resolution of 640x480 in monochrome, the font size is 8x16, which allows
for 80x30 characters.

Link: http://vasyaod-blog.tumblr.com/post/34422942376/stm32-vga-text-terminal

Author: vasyaod (vasyaod@mail.ru)

## Changes compared to the original project

The project is modified to support STM32F103C8, which doesn't have TIM5. Also,
it is changed to build under Atollic TrueStudio 9.0.

## How to connect wires:

| PIN | Description | Connect To | Output |
| --- | ----------- | ---------- | ------ |
| PA7 | Green | Resistor 280 Ohm | VGA green (2)
| PA6 | HSync | | VGA HSync (13)
| PA1 | VSync | | VGA VSync (14)
| G | Ground | | VGA Ground (5,6,7,8,10)
