# Port Scanner Tool

## Description

The Port Scanner Tool is a simple Python script that allows you to scan ports on a target IP address or hostname. It uses multithreading for faster scanning and provides basic service information using Nmap.

## Features

- **Multithreaded Scanning**: The tool uses multithreading to scan multiple ports concurrently.
- **Nmap Integration**: Provides additional service information using Nmap for open ports.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/MrYellowOwl/GotPorts.git
    ```

2. Navigate to the project directory:

    ```bash
    cd GotPorts
    ```

3. Run the script:

    ```bash
    python3 GotPorts.py
    ```

4. Follow the on-screen instructions to enter the target IP address or hostname.

## Requirements

- Python 3.x
- Nmap (for service detection)

## Customization

Feel free to customize the banner and ASCII art in the `print_banner()` function in the `gotports.py` script.

## Acknowledgements

- ASCII art by [Mr Yellow Owl](https://github.com/mryellowowl)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Issues and Contributions

If you encounter any issues or have suggestions for improvements, please [open an issue](https://github.com/your-username/port-scanner-tool/issues). Contributions are welcome!

---

**By Mr Yellow Owl**

[GitHub Profile](https://github.com/mryellowowl)
