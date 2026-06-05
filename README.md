# Inspire

A simple terminal tool that displays random inspirational quotes whenever you need them.

## How to Install (Should Work on Most Linux Distros)

Open your terminal and run these commands:

```bash
# Create local bin directory if it doesn't exist
mkdir -p ~/.local/bin

# Download the script directly to your local bin folder
curl -sL https://raw.githubusercontent.com/D0ct0rDub/terminal-inspire/main/inspire -o ~/.local/bin/inspire

# Make the script executable
chmod +x ~/.local/bin/inspire
```
Please open an issue if this command doesn't work on your distro (after you have tried the recommended steps in the troubleshooting section).
## Usage

```bash
inspire
```

### Troubleshooting

If your terminal says `command not found` after installing, your system might not look in your local bin folder automatically. Fix this by adding it to your PATH:

```bash
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

## Updating

For now, updating Inspire is run via reinstalling the project

To update Inspire to the latest version, re-run the installation commands:

```bash
curl -sL https://raw.githubusercontent.com/D0ct0rDub/terminal-inspire/main/inspire -o ~/.local/bin/inspire

chmod +x ~/.local/bin/inspire
```

There are future plans for updates to be run through a terminal command such as:

```bash
inspire --update
```
