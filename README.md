## IRX - Infrared Remote Library for Proteus
IRX is an open-source library designed for use with the Proteus simulation software, enabling the simulation of IR (Infrared) remote control functionality for various devices. The library provides support for a range of IR protocols, making it compatible with popular brands like SONY, CHINA TV, MP3 players, and RGB controllers. With IRX, you can seamlessly integrate IR remote control simulation into your microcontroller projects, such as Arduino, AVR, PIC, and STM, using Proteus.

__Note:__ This library requires a minimum of Proteus version 8.12 or later.

## Features
- __Wide Protocol Support:__ IRX supports a variety of IR protocols, including SONY, CHINA TV, MP3, and RGB remote control protocols.
- __Easy Integration:__ Incorporating IRX into your Proteus simulations is straightforward, allowing you to add IR remote functionality to your microcontroller projects with ease.
- __Microcontroller Compatibility:__ IRX is designed to work with popular microcontroller platforms such as Arduino, AVR, PIC, and STM, providing a versatile solution for a wide range of simulation scenarios.
- __Customizable:__ The library is designed to be flexible, allowing you to create custom IR remote scenarios tailored to your simulation needs.
- __User-Friendly:__ Even if you're new to IR simulations, IRX's intuitive interface and comprehensive documentation will guide you through the setup process.
- __Open-Source:__ IRX is an open-source project, inviting collaboration and contributions from the community to improve and extend its functionality.

## Getting Started
To use the IRX library in your Proteus simulations, follow these steps:

- __Prerequisites:__ Ensure you have Proteus version 8.12 or newer installed on your system.
- __Installation:__ Download the [IRX library](https://github.com/chayanforyou/IRX-Proteus/releases/latest) from the latest release.
- __Integration:__ Unzip `IRX_Library.zip`. Add the `IRX.LIB` to `DATA > LIBRARY` and `IRX.IDX` to `DATA > Library Indexing`.
- __Simulation:__ Select a Remote of your choice from the Device Pickup, Configure the MCU and run the simulation. 

## Example Usage
Here's a basic example of how to use the IRX library

[YouTube Demo](https://youtu.be/cvsGcb-TSkk)

#### Arduino

![](Simulation/IRX%20with%20Arduino%20UNO/IRX_Arduino.png)

#### PIC12F675

![](Simulation/IRX%20with%20PIC12F675/IRX_PIC12F675.png)

## Contributing
We welcome contributions to the IRX library! If you have improvements, bug fixes, or new remotes to add.

## Special Thanks
To [Antor Ahmed](https://github.com/AntorOfficial)

## Acknowledgments
A big thank you to the following third-party libraries and projects that made IRX possible:

- [irdb](https://github.com/probonopd/irdb)
- [decodeir](https://github.com/probonopd/decodeir)
- [MakeHex](https://github.com/probonopd/MakeHex)
- [IrScrutinizer](https://github.com/bengtmartensson/IrScrutinizer)

## Contact
If you have any questions, suggestions, or feedback, feel free to contact.

[chayanmistrry@gmail.com](mailto:chayanmistrry@gmail.com)

## License
IRX is released under the [MIT License](LICENSE).
```
Copyright (c) 2023 Chayan Mistry
All rights reserved.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
