# Network Spoofer & Packet Dumper

## Overview

This CLI application is designed for network spoofing and dumping network packets. It allows you to simulate various network scenarios and capture traffic for analysis. This tool is intended for educational purposes and network testing.

## Features

- Network packet spoofing
- Packet dumping and logging
- Command-line interface for easy use

## Prerequisites

- Python 3
- Administrative or root privileges for network access on running device

## Installation

**Clone the repository:**

```bash
git clone https://github.com/abdullahbagyapan/network-spoof.git
cd network-spoof
```

## Available Commands

Use the `--help` flag with any command to see more details:

```bash
usage: spoofy.py [-h] -n NET_INTERFACE -i IP_ADDRESS

A simple CLI for spoofing network and dumping traffic

options:
  -h, --help            show this help message and exit
  -n NET_INTERFACE, --net_interface NET_INTERFACE
                        The network interface that is going out whole network
  -i IP_ADDRESS, --ip_address IP_ADDRESS
                        The ip address that is going in whole network```
```

## Contributing

Contributions are welcome! Please submit a pull request or open an issue if you have any suggestions or find any bugs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

**This tool is intended for educational and legitimate network testing purposes only. Unauthorized use of network spoofing and packet capturing may be illegal and unethical. Ensure you have permission to test and analyze network traffic in any environment you use this tool.**