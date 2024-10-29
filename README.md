# Pwnagotchi Setup Guide

## Thanks
- **Base Image**: Huge thanks to [jayfelony](https://github.com/jayfelony) for providing the base Pwnagotchi image.
- **Plugins**: Big thanks to [SHUR1K-N](https://github.com/SHUR1K-N) for the custom plugins used in this setup.

---

## Step 1: Download and Install the Base Image
1. Download the Pwnagotchi base image provided by jayfelony [here](https://github.com/jayofelony/pwnagotchi).
2. Flash the image to your SD card using a tool like [Balena Etcher](https://www.balena.io/etcher/).

## Step 2: Download Custom Plugins
1. Connect to your Pwnagotchi using FileZilla to upload plugins:
   - **Host**: Use the Pwnagotchi’s IP address (you can find this in your router settings or use `pwnagotchi.local` if available).
   - **Username**: `pi`
   - **Password**: (default is `raspberry`)
2. Download SHUR1K-N’s custom plugins from [SHUR1K-N’s repository](https://github.com/SHUR1K-N/pwnagotchi-plugins).
3. In FileZilla, upload these plugins to the `/usr/local/share/pwnagotchi/custom-plugins/` directory on the Pwnagotchi.

## Step 3: Configuration File Setup

 A file called config.toml in /etc/pwnagotchi is responsible for configuring the entire behavior of the Pwnagotchi, including network settings, plugins, display options, and AI learning parameters.

# I have added a config.toml file which you can edit and customize!

VOILA!
Your Pwnagotchi can capture handshakes with enhanced functionality. Enjoy hacking responsibly!
