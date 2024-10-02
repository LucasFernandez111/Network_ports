# list_ports.sh

**Description**: `list_ports.sh` is a Bash script designed to list active ports and associated processes on Windows and Linux operating systems. It allows filtering the output by a specific PID using the `-f` option. The script displays information about ports, PIDs, and service names in color for improved readability.

## Features

- **List Active Ports**: Displays active ports and their associated processes.
- **PID Filtering**: Filter the output by a specific PID using the `-f` option.
- **Cross-Platform Compatibility**: Works on both Windows (via Git Bash or WSL) and Linux.

## Usage

- To filter the output by a specific PID, use the `-f` option:
  ```bash
  ./network_ports.sh -f <PID>

