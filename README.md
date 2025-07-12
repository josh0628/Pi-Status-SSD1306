# Pi-Status-SSD1306: Monitor Your Raspberry Pi with SSD1306 Display

![SSD1306 Display](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/OLED_Display_SSD1306.jpg/800px-OLED_Display_SSD1306.jpg)

![GitHub Releases](https://img.shields.io/badge/releases-latest-blue.svg) [![Download](https://img.shields.io/badge/download-latest%20release-brightgreen.svg)](https://github.com/josh0628/Pi-Status-SSD1306/releases)

## Overview

Pi-Status-SSD1306 provides a simple way to display key system information on an SSD1306 OLED screen. This project is designed for Raspberry Pi users who want to monitor their system's status in real-time. 

## Features

- Display CPU usage
- Show memory usage
- Monitor disk space
- Real-time updates
- Lightweight and easy to set up

## Getting Started

To get started with Pi-Status-SSD1306, follow these steps:

### Prerequisites

- Raspberry Pi (any model)
- SSD1306 OLED display
- Python 3 installed on your Raspberry Pi
- I2C enabled on your Raspberry Pi

### Installation

1. **Clone the Repository**

   Open your terminal and run the following command:

   ```bash
   git clone https://github.com/josh0628/Pi-Status-SSD1306.git
   ```

2. **Navigate to the Directory**

   Change to the project directory:

   ```bash
   cd Pi-Status-SSD1306
   ```

3. **Install Required Libraries**

   Use pip to install the necessary Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

### Configuration

Before running the script, ensure your SSD1306 display is connected properly. Check the wiring:

- VCC to 3.3V or 5V
- GND to Ground
- SCL to GPIO 3 (SCL)
- SDA to GPIO 2 (SDA)

### Running the Script

To start displaying system information, run the following command:

```bash
python3 main.py
```

The script will now display the CPU usage, memory usage, and disk space on the SSD1306 screen.

## Usage

Once the script is running, you will see the following information on your display:

- **CPU Usage**: Shows the percentage of CPU currently in use.
- **Memory Usage**: Displays the amount of RAM being used.
- **Disk Space**: Indicates the available disk space on your Raspberry Pi.

You can stop the script at any time by pressing `Ctrl + C`.

## Troubleshooting

If you encounter issues, check the following:

- Ensure I2C is enabled on your Raspberry Pi. You can enable it via `raspi-config`.
- Verify the connections between the Raspberry Pi and the SSD1306 display.
- Check if the required libraries are installed correctly.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to create an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest releases, please visit the [Releases section](https://github.com/josh0628/Pi-Status-SSD1306/releases). You can download the latest version and execute it on your Raspberry Pi.

## Topics

This project covers various topics including:

- **i2c**: The communication protocol used for the SSD1306 display.
- **monitoring**: The purpose of the project is to monitor system performance.
- **pi**: Specifically designed for Raspberry Pi.
- **python**: The programming language used.
- **raspberry-pi**: The hardware platform.
- **ssd1306**: The display model used in this project.

## Support

If you have any questions or need support, feel free to open an issue on GitHub. The community is here to help.

## Acknowledgments

- Thanks to the contributors of the libraries used in this project.
- Special thanks to the Raspberry Pi Foundation for creating such an accessible platform for learning and development.

![Raspberry Pi](https://www.raspberrypi.org/app/uploads/2018/03/Raspberry-Pi-Logo.png)

## Additional Resources

- [Raspberry Pi Documentation](https://www.raspberrypi.org/documentation/)
- [SSD1306 OLED Display Datasheet](https://cdn.sparkfun.com/datasheets/LCD/SSD1306.pdf)
- [Python I2C Documentation](https://pypi.org/project/smbus2/)

For more information, feel free to check the [Releases section](https://github.com/josh0628/Pi-Status-SSD1306/releases) again.