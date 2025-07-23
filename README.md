# Depth Pre-Pass and Overdraw Visualizer

This is a graphics demo showcasing a depth pre-pass and overdraw visualization technique built using a modified version of The Forge Framework's Triangle Visibility Buffer pipeline.

## Features
- Pixel shader based overdraw visualizer
- Depth pre-pass implementation

## Building
This project requires The Forge dependencies to be installed. Follow these steps:

1. Clone this repo
2. Clone and build The Forge Framework separately. See: [The Forge Setup Guide](https://github.com/ConfettiFX/The-Forge)
2. Ensure you have Visual Studio 2019 and the Windows 10 SDK
3. Copy Visibility_Buffer.cpp and Shaders folder into The-Forge\Examples_3\Visibility_Buffer\src Replace files if prompted
4. Open The-Forge\Examples_3\Visibility_Buffer\PC_VS2019\Visibility_Buffer.sln
in Visual Studio 2019 and run the project

## Acknowledgements
This project is based on [The Forge](https://github.com/ConfettiFX/The-Forge), licensed under Apache 2.0.

Modifications by Nathan Keith (2025).

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for more information.
