# LED Matrix Control Software HD <img src="https://github.com/gmanandmarbles/Awesome-Event-Systems/assets/119905567/d19eb3fd-40c4-4d3c-aa4e-3237b991602f" align="right" height="258"/>


## Overview
The aim of this project is to create a fully featured software that allows users to easily display animations and images on their own custom LED matrix. LMCSHD can either send image data to a matrix in real-time using a standard UART Serial connection, or export the image in a variety of formats for later use. 

This version of the LMCS can support very high resolution matrices, hence LMCS-_**HD**_

## Features
* Real-time screen capture and mirroring
* Displaying various images and .gif files
* Real-time Audio spectrum analysis and graphing
* Pixel art style drawing
* Image exporting to a variety of formats

## Setup
Grab the latest release for a stable build [here](https://github.com/TylerTimoJ/LMCSHD/releases)

see [this](https://docs.google.com/spreadsheets/d/1Yj7z65aB2vSuuKZ2YIDSMPz1oNud_M95WxM7BJwhVwQ/edit?usp=sharing) Google Sheet detailing the serial protocol

Requires .NET Framework 4.7.2

## Usage
Under the `Serial` menu tab click `Connect`. Specify the correct COM port, baud rate, and color mode. Assuming the matrix uses the correct serial protocol (as specified in protocol.txt), the matrix width and height should be read by the application. From there, select one of the modes and whatever’s displayed on the matrix preview should be mirrored to the physical matrix.

If a serial connection is not available, or not applicable, everything can be used normally, and the resulting images can be exported under the `File` menu tab and `Export`.

## Contributing
Thanks: benmartens!

Help with the development of LMCSHD is greatly appreciated, and necessary. Help can be provided in a number of ways
* Leaving feedback, or suggestions on the various [YouTube showcase videos](https://www.youtube.com/watch?v=LmrzyJAwyCQ&list=PLt5bhXqA0WNq3WJG-4qe4-SQdlFvXctAs) associated with the project
* Reporting issues
* Directly contributing to the project’s source code

## License
Microsoft Public License - An open source license with a patent grant.
See [License](https://github.com/TylerTimoJ/LMCSHD/blob/master/LICENSE)
