```markdown
# Leaf 🍃 - Simple Daily Journaling CLI

A simple command-line tool for daily journaling that syncs with Nextcloud.

## Features

- 🍃 Beautiful daily journal templates
- 🔍 Search through all entries
- 📱 Mobile editing via Nextcloud sync
- 📝 Plain text files you own forever

## Installation

```bash
# Make the script executable
chmod +x leaf

# Copy to system path
sudo cp leaf /usr/local/bin/leaf
```

## Usage

```bash
leaf              # Open today's journal
leaf yesterday    # Open yesterday's entry
leaf find "term"  # Search all entries
leaf list         # Show recent entries
leaf setup        # Initial setup
leaf help         # Show help
```

## Setup

1. Run `leaf setup` to create the journal directory
2. Start journaling with `leaf`
3. Journal files are saved to `~/Nextcloud/Notes/Leaf/`

## Mobile Access

Use QuillPad or Nextcloud Notes app to edit entries on your phone.
Files sync automatically via Nextcloud.

## License

MIT License
```
