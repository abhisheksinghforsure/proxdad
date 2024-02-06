# ProxDad

ProxDad is a collection of bash scripts designed to simplify the management of proxy settings in Linux environments. It provides a set of utilities to quickly configure and switch between different proxy settings, making it easier for users to adapt to varying network configurations.

## Features

- Easily switch between different proxy configurations.
- Supports HTTP, HTTPS, FTP, and SOCKS proxies.
- Simple command-line interface for convenient usage.
- Lightweight and easy to install.

## Installation

1. Clone the ProxDad repository:

```bash
git clone https://github.com/abhisheksinghforsure/proxdad.git
```

2. Navigate to the ProxDad directory:

```bash
cd proxdad
```

3. Give executable permission to the installation and uninstallation scripts:

```bash
chmod +x install uninstall
```

4. Run the installation script:

```bash
./install
```

5. Follow the prompts to configure your proxy settings. You can choose to use default settings or set them manually.

6. Once the installation is complete, ProxDad is ready to use.

## Usage

1. Open a new terminal.

2. To turn on ProxDad, type the following command:

```bash
onproxdad
```

3. To turn off ProxDad, type the following command:

```bash
offproxdad
```

4. To check whether ProxDad is on or off, type the following command:

```bash
statusproxdad
```

For more detailed usage instructions and options, refer to the documentation in the `docs` directory.

## Compatibility

ProxDad is compatible with most Linux distributions. However, it is primarily tested on Ubuntu and Debian-based systems.

## Contributing

Contributions to ProxDad are welcome! If you have any ideas for improvements, feature requests, or bug fixes, please open an issue or submit a pull request on GitHub.

## License

ProxDad is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Disclaimer

ProxDad is provided as-is without any warranty. Use at your own risk.
