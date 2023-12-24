# vesktop-void-template

This repository provides a template for installing Vesktop on Void Linux, specifically tailored for systems with GCC version 13 or higher. It's designed to simplify the process of setting up Vesktop, ensuring compatibility and ease of use on Void Linux environments.

## Prerequisites
Ensure that your system has **GCC 13 or newer** installed, as Vesktop requires it for optimal performance. For detailed guidance on setting up your environment, please refer to the `run.sh` script included in this repository to see how it is run.

## Installation Steps
1. **Script Setup**: Place the `run.sh` script in the `/opt/Vesktop` directory. This script is crucial for correctly configuring the runtime environment for Vesktop.
2. **Desktop Entry**: To integrate Vesktop seamlessly with your desktop environment, use the provided `.desktop` file. Copy this file to `~/.local/share/applications` to make Vesktop accessible from your application menu.

## Note
The `run.sh` script contains important information about configuring your system to use Vesktop. It's recommended to review this script for a deeper understanding of the installation process and requirements.

By following these steps, users can enjoy a smooth Vesktop experience on their Void Linux system. Contributions, suggestions, and feedback are always welcome!
