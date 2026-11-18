# SagemMorphoUI

Qt desktop application for connecting to Sagem Morpho fingerprint terminals over a serial port. It combines a terminal view with Morpho protocol commands and response decoding.

## Features

- Configure the serial port, baud rate, data bits, parity, stop bits, and flow control.
- Send terminal commands and Morpho operations for identification, cancellation, and database management.
- Build and parse Morpho ILV packets, including CRC validation, byte stuffing, acknowledgements, and response status reporting.
- Inspect device communication in the built-in terminal.

## Screenshots

![SagemMorpho1 GUI](https://codeleccz.github.io/SagemMorphoUI/screenshots/Sagem01.png)
![SagemMorpho2 GUI](https://codeleccz.github.io/SagemMorphoUI/screenshots/Sagem02.png)
![SagemMorpho3 GUI](https://codeleccz.github.io/SagemMorphoUI/screenshots/Sagem03.png)

## Build

The application uses Qt Widgets and Qt Serial Port. Open `SagemMorphoUI.pro` in Qt Creator, select a Qt kit with those modules, and build the project.

## Article

- [Česky](blog/index.cs.md)
- [English](blog/index.en.md)
