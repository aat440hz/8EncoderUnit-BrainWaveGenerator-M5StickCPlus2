# 8EncoderUnit BrainWave Generator for M5StickC Plus2

This Arduino project designed for the M5StickC Plus2 utilizes the 8Encoder Unit inputs to generate brainwave-like audio frequencies and provides real-time visualization on an oscilloscope. This project enables users to experiment with various frequencies and pulse rates to create audiovisual patterns.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Generate audio frequencies resembling brainwave patterns.
- Visualize the generated audio on an oscilloscope.
- Real-time adjustment of frequencies and pulse rates.
- Toggle between playing and stopping the audio generation.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Arduino IDE](https://www.arduino.cc/en/software) installed on your computer.
- An [M5StickC Plus2](https://docs.m5stack.com/en/core/M5StickC%20PLUS2) device.
- 1 [8Encoder unit](https://shop.m5stack.com/products/8-encoder-unit-stm32f030)
- [UNIT_8ENCODER library](https://github.com/m5stack/M5Unit-8Encoder) installed in your Arduino IDE.

## Getting Started

1. Clone this repository to your local machine:

2. Open the Arduino IDE and load the Arduino sketch (`8EncoderUnit_BrainWave_Generator.ino`) from the cloned repository.

3. Connect your M5StickC Plus2 device to your computer using a USB cable.

4. Upload the sketch to your M5StickC Plus2 device.

## Usage

1. Connect your M5StickC Plus2 device to a power source.

2. Use a web browser on a device connected to the Brainwave Generator WiFi network to access the audio visual interface by entering the M5StickC Plus2 IP address in the address bar (192.168.4.1) and click play.

3. Adjust the frequencies and pulse rate using the 8Encoder Unit.

4. Click Button A on the M5StickCPlus2 to start generating audio frequencies. Click it again to stop the generation.

5. Visualize the audio patterns on the oscilloscope displayed on the web interface.

6. Experiment with different frequency settings to create unique audiovisual experiences.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature`.

3. Make your changes and commit them: `git commit -m 'Add some feature'`.

4. Push to the branch: `git push origin feature/your-feature`.

5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
