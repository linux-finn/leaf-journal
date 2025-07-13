```markdown
# Installation Guide 🚀

## Prerequisites

- Linux, macOS, or Windows with WSL
- Bash shell
- Git (for installation)
- Nextcloud account (optional but recommended)

## Method 1: Git Clone (Recommended)

```bash
# Clone the repository
git clone https://github.com/linux-finn/leaf-journal.git
cd leaf-journal

# Make executable
chmod +x leaf

# Install system-wide
sudo cp leaf /usr/local/bin/

# Verify installation
leaf help
```

## Method 2: Direct Download

```bash
# Download the script directly
curl -O https://raw.githubusercontent.com/linux-finn/leaf-journal/main/leaf

# Make executable
chmod +x leaf

# Install system-wide
sudo cp leaf /usr/local/bin/

# Verify installation
leaf help
```

## Initial Setup

```bash
# Run setup (creates journal directory)
leaf setup

# Start your first journal entry
leaf
```

## Nextcloud Integration

1. **Install Nextcloud desktop client** or ensure sync folder exists
2. **Run setup** - Leaf will automatically find your Nextcloud folder
3. **Manual path** - If auto-detection fails, edit the script:
   ```bash
   sudo nano /usr/local/bin/leaf
   # Change LEAF_DIR to your Nextcloud path
   ```

## Mobile Setup

### Android (QuillPad)
1. Install QuillPad from Play Store
2. Add Nextcloud account
3. Navigate to Notes/Leaf/ folder
4. Edit any journal entry

### iOS (Nextcloud Notes)
1. Install Nextcloud Notes from App Store
2. Connect to your Nextcloud account
3. Browse to Leaf folder
4. Edit journal entries

## Troubleshooting

### Command not found
```bash
# Check if /usr/local/bin is in PATH
echo $PATH

# If not, add to ~/.bashrc:
export PATH="/usr/local/bin:$PATH"
source ~/.bashrc
```

### Permission denied
```bash
# Make sure script is executable
chmod +x /usr/local/bin/leaf

# Check ownership
ls -la /usr/local/bin/leaf
```

### Nextcloud not found
```bash
# Edit script to set custom path
sudo nano /usr/local/bin/leaf

# Change this line:
LEAF_DIR="$HOME/your/custom/path"
```

## Uninstall

```bash
# Remove the script
sudo rm /usr/local/bin/leaf

# Optionally remove journal files
rm -rf ~/Nextcloud/Notes/Leaf/
```
```
