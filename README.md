# SagemMorphoUI

Qt desktop application for connecting to Sagem Morpho fingerprint terminals over a serial port. It combines a custom serial-command prompt with a separate Morpho binary-protocol implementation.

## Features

- Configure the serial port, baud rate, data bits, parity, stop bits, and flow control.
- Send application-specific text commands over the serial port, separately from Morpho protocol operations for identification, cancellation, and database management.
- Build and parse Morpho ILV packets, including CRC validation, byte stuffing, acknowledgements, and response status reporting.
- Inspect device communication in the built-in terminal.

## Screenshots

![Initialization](screenshots/sagem0.png)<br><strong>1. Initialization</strong>

![Biometric operations](screenshots/sagem1.png)<br><strong>2. Biometric</strong>

![Database management and an example data trace](screenshots/sagem2.png)<br><strong>3. Database management and an example of a data trace</strong>

## Build

The application uses Qt Widgets and Qt Serial Port. Open `SagemMorphoUI.pro` in Qt Creator, select a Qt kit with those modules, and build the project.

## Article

- [Česky](blog/index.cs.md)
- [English](blog/index.en.md)
