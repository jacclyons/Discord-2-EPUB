# Discord → EPUB 📚

Convert your Discord chat exports into beautiful, readable EPUB files. Perfect for preserving roleplaying campaigns, creative collaborations, or memorable conversations.

## ✨ Features

- **📖 Single & Multi-Chat Support**: Process one chat or combine multiple conversations chronologically
- **⏱️ Smart Chaptering**: Automatically detects GM separators (lines of dashes) to create logical chapter breaks
- **🖼️ Image Embedding**: Includes images directly in the EPUB
- **✏️ Author Renaming**: Click any author name to rename them for the final book
- **🎵 Spotify Integration**: Converts Spotify links to formatted song titles
- **📅 Chronological Merging**: Multiple chats are interweaved by timestamp to create a coherent story

## 🚀 Quick Start

1. **Open the tool**: Just open `discordEPUB.html` in your browser (no installation needed!)
2. **Choose your mode**:
   - 👤 **Solo Chat**: Single conversation from one export
   - 👥 **Duo Chat**: Multiple conversations merged chronologically
3. **Drop your ZIP file(s)**: Drag and drop your Discord Chat Exporter ZIP files
4. **Parse & Preview**: Click "Parse Export" to see your messages
5. **Customize** (optional):
   - Edit the book title
   - Rename authors by clicking their names
6. **Download**: Click "Save EPUB" to get your book!

## 📂 What You Need

Export your Discord chats using [DiscordChatExporter](https://github.com/Tyrrrz/DiscordChatExporter):
- Include **messages** (JSON or HTML format)
- Include **media files** in the `_media` folder
- Package everything as a **ZIP file**

## 🎭 Perfect For

- **D&D Campaigns**: Turn your game sessions into readable novels
- **Roleplay Stories**: Preserve collaborative storytelling
- **Creative Projects**: Archive brainstorming and development conversations
- **Memories**: Keep important conversations in a portable format

## 🔧 How It Works

### Solo Chat Mode
1. Processes a single Discord export
2. Uses separator messages (lines of dashes) as chapter markers
3. Creates an EPUB with natural chapter breaks

### Duo Chat Mode
1. Accepts multiple Discord export files
2. **Merges all messages chronologically by timestamp**
3. Creates a single unified story
4. Uses separators from any chat to mark chapter breaks
5. Perfect for parallel conversations that should be read together

## 💡 Tips

- **Chapter Breaks**: Use lines of dashes (`--------------------`) in Discord to mark where chapters should start
- **Author Names**: The tool auto-detects Discord display names, but you can rename anyone for the final EPUB
- **Images**: Make sure to export with media files for images to embed properly
- **File Naming**: For duo chats, filenames help identify which conversation is which

## 🎨 Interface

- **Minimalist Design**: Clean, dark interface with icon-only controls
- **Live Preview**: See your messages before generating the EPUB
- **Drag & Drop**: Easy file upload experience
- **Author Management**: Quick editing of author names

## 📝 Technical Details

- Pure HTML/JavaScript - no server required
- Uses JSZip for archive handling
- EPUB 3.0 format output
- Processes Discord Chat Exporter JSON and HTML formats
- Chronological message sorting with timezone handling
- Smart image matching across multiple export formats

## 🤝 Contributing

Found a bug? Have a feature request? Open an issue or submit a PR!

## 📜 License

MIT License - feel free to use, modify, and share!

---

**Made with ❤️ for preserving digital memories**
