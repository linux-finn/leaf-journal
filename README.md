```markdown
# Leaf 🍃 - Simple Daily Journaling CLI

A beautiful command-line tool for daily journaling that syncs seamlessly with Nextcloud.

## ✨ Features

- 🍃 **Daily journal templates** with emoji sections for mood, weather, and reflections
- 🔍 **Powerful search** through all your journal entries
- 📱 **Mobile editing** via Nextcloud sync (QuillPad, Nextcloud Notes)
- 📝 **Plain text files** - you own your data forever, no vendor lock-in
- 🔄 **Cross-device sync** - write anywhere, access everywhere
- ⚡ **Lightning fast** - CLI speed with beautiful templates

## 🚀 Quick Start

```bash
# Download and install
git clone https://github.com/linux-finn/leaf-journal.git
cd leaf-journal
chmod +x leaf
sudo cp leaf /usr/local/bin/

# Setup and start journaling
leaf setup
leaf
```

## 📋 Commands

| Command | Description |
|---------|-------------|
| `leaf` | Open today's journal entry |
| `leaf yesterday` | Open yesterday's entry |
| `leaf find "keyword"` | Search all journal entries |
| `leaf list` | Show recent entries |
| `leaf setup` | Initial setup |
| `leaf help` | Show help menu |

## 📱 Mobile Access

Leaf works beautifully with mobile apps:

- **QuillPad** (Android) - Full Nextcloud integration
- **Nextcloud Notes** (iOS/Android) - Official app
- **Any text editor** that supports Nextcloud

Your journal entries sync automatically across all devices!

## 🎯 Daily Template

Each journal entry includes structured sections:

```
🍃 Saturday, July 13, 2025

🌤️ Weather: 
😊 Mood: 
⚡ Energy: 

🌅 Morning intentions:


🎯 Day's highlights:


🤔 Reflections:


🙏 Grateful for:


🌱 Tomorrow's focus:

```

## 🛠️ Setup Requirements

- **Bash shell** (Linux, macOS, WSL)
- **Nextcloud account** (for sync - optional but recommended)
- **Text editor** (nano, vim, kate, etc.)

## 📂 File Organization

```
~/Nextcloud/Notes/Leaf/
├── 2025-07-13.txt    # Today's entry
├── 2025-07-12.txt    # Yesterday's entry
├── 2025-07-11.txt    # Previous entries
└── ...               # Years of journal history
```

## 🔍 Search Examples

```bash
# Find entries about work
leaf find "meeting"

# Look for mood patterns  
leaf find "mood: good"

# Search for gratitude entries
leaf find "grateful"
```

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🌟 Why Leaf?

> "Each day is a new leaf in the story of your life"

Leaf helps you build a sustainable journaling habit with:
- **Simplicity** - One command to start writing
- **Consistency** - Beautiful templates every day  
- **Longevity** - Plain text files that last forever
- **Accessibility** - Works on any device, any platform

---

**Start your journaling journey today with `leaf`** 🍃
```
