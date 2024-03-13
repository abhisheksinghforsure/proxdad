# ProxDad

ProxDad is a collection of bash scripts designed to simplify the management of proxy settings in Linux environments. It provides a set of bash scipts to quickly turn ON or OFF proxy settings for different applications.

## Features 

ProxDad configures proxy settings for following applications:

- Environment variables for system-wide use.
- APT (Advanced Package Tool) for package management.
- GNOME proxy applet settings.
- Git for version control.
- npm (Node Package Manager) for Node.js packages.
- Snap for managing snap packages.
- SSH for secure shell connections.

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
chmod +x install
```

4. Run the installation script:

```bash
./install
```

5. Follow the prompts to configure your proxy settings. You can choose to use default settings or set them manually.
6. Once the installation is complete, ProxDad is ready to use.

## Usage

1. Open a new terminal.
2. To turn ON ProxDad, type the following command:

```bash
onpxd
```

3. To turn OFF ProxDad, type the following command:

```bash
offpxd
```

4. To check whether ProxDad is ON or OFF, type the following command:

```bash
statuspxd
```

5. To check help for ProxDad, type the following command:

```bash
proxdad -h
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
