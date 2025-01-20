# podman-lynx
# Podman Container Management Tool

**Disclaimer:** This tool is provided for educational and ethical use only. Use of this script for unauthorized access or any activity against terms of service or laws is strictly prohibited. The author assumes no responsibility for misuse. Always ensure you have permission for any container-related operations.

A Bash script designed for users who prefer using Podman for container management, offering features that enhance security and privacy over traditional Docker usage.

## Features

- **Run Containers**: Start, stop, and manage containers with Podman's security-focused approach.
- **Image Management**: Pull, list, and remove container images securely without the need for a daemon.
- **Rootless Containers**: Run containers without root privileges for enhanced security.
- **Network Isolation**: Manage network settings for containers to keep your activities private.
- **Resource Limitation**: Control how much CPU, memory, etc., your containers can use for better system resource management.
- **Pod Management**: Create and manage pods for grouping containers that share namespaces.

## Why Podman?

Podman is like playing with your toys in a sandbox where each toy (container) has its own safe space. Unlike Docker, which needs a constant supervisor (daemon), Podman lets you play directly with your toys, making it safer because there's no big "boss" watching everything. Here's how it works:

- **No Daemon**: No background service running all the time, which means less chance for someone to sneak in through a backdoor.
- **Rootless**: You can play with your toys in your own space without needing to be the "king" (root) of the playground. This makes it harder for bad guys to take over if they manage to get into one of your toys.
- **Privacy**: Your toys can talk to each other privately, and you can control who sees them on the network.

## Installation

1. Clone this repository:
   ```bash
   git clone git@github.com:QueBickle/podman-tools.git
   cd podman-tools
