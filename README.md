# ProxDad 

[![Platform: Linux](https://img.shields.io/badge/Platform-Linux-red)](#)
[![Script: Bash](https://img.shields.io/badge/Script-Bash-brightgreen)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/abhisheksinghforsure/proxdad/blob/main/LICENSE)

ProxDad is a set of bash scripts that simplifies proxy settings management in Linux environments. It provides an easy way to toggle proxy settings ON or OFF for various applications.

## Features 

> ProxDad configures proxy settings for the following applications:

- Environment variables for system-wide use.
- APT (Advanced Package Tool) for package management.
- GNOME proxy applet settings.
- KDE proxy applet settings.
- Git for version control.
- npm (Node Package Manager) for Node.js packages.
- Snap for managing snap packages.
- SSH for secure shell connections.

## Installation

Watch ProxDad Installation and Usage Tutorial on YouTube 👇

[![Video](https://img.youtube.com/vi/ypCnVTdO_J8/maxresdefault.jpg)](https://www.youtube.com/watch?v=ypCnVTdO_J8)

1. Clone the ProxDad repository:

```bash
git clone https://github.com/abhisheksinghforsure/proxdad.git
```

2. Navigate to the ProxDad directory:

```bash
cd proxdad
```

3. Give executable permission to the installation scripts:

```bash
chmod +x install
```

4. Run the installation script:

```bash
./install
```

5. Follow the prompts to configure proxy settings. You can choose to use default settings or set them manually.
6. Once the installation is complete, ProxDad is ready to use.

## Usage

Open a new terminal.

- To check usage of ProxDad, type the following command:

```bash
proxdad --help
```

- To turn ON ProxDad, type the following command:

```bash
onpxd
```

- To turn OFF ProxDad, type the following command:

```bash
offpxd
```

- To check status of ProxDad, type the following command:

```bash
statuspxd
```

- To restart ProxDad, type the following command:

```bash
restartpxd
```

- To config proxy settings for ProxDad, type the following command & check help:

```bash
setpxd --help
```

## Uninstallation

To uninstall ProxDad, type the following command: 

```bash
uninstallpxd
```

## Compatibility

ProxDad is compatible with most Linux distributions. However, it is primarily tested on **Ubuntu** and **Debian-based systems**.

## Contributing

Contributions to ProxDad are welcome! If you have any ideas for improvements, feature requests, or bug fixes, please open an issue or submit a pull request on GitHub.

## License

ProxDad is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Disclaimer

ProxDad is provided as-is without any warranty. Use at your own risk.
