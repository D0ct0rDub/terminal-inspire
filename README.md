# Inspire Command

A terminal tool that should work across any distro, in order to get random inspirational quotes in your time of need.

## How to Install (Should Work on Most Linux Distros, please inform me if it does not)

Open your terminal and run these commands:

```bash
# Create local bin directory if it doesn't exist
mkdir -p ~/.local/bin

# Download the script directly to your local bin folder
curl -sL https://raw.githubusercontent.com/D0ct0rDub/terminal-inspire/main/inspire -o ~/.local/bin/inspire

# Make the script executable
chmod +x ~/.local/bin/inspire
```

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
