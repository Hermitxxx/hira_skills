# Hira Skills

Custom skills collection for AI agent platforms including Antigravity, Claude Code, and Cursor.

## Included Skills

### tech-vid-script-v3 (Master Multi-Device)
A comprehensive video scriptwriting skill for YouTube technology tutorials and troubleshooting guides across all operating systems and devices.

### Device-Specific Skills (`<device>-script`)
- **`/android-script`**: Dedicated to Android smartphones and tablets (Xiaomi HyperOS/MIUI, Samsung One UI, Google Pixel, OnePlus). Includes an Android notification troubleshooting template.
- **`/windows-script`**: Dedicated to Windows PCs (Windows 11 and Windows 10 desktops and laptops). Includes a Windows 11 Dark Mode setup template.
- **`/mac-script`**: Dedicated to Apple Mac computers and macOS (MacBook Pro/Air, iMac, Mac mini). Includes a Mac trackpad secondary-click template.
- **`/switch-script`**: Dedicated to Nintendo Switch consoles (Switch, Switch OLED, Switch Lite). Includes a console battery percentage display template.
- **`/ps5-script`**: Dedicated to Sony PlayStation consoles (PS5, PS5 Slim, PS5 Pro, PS4). Includes a DualSense microphone auto-mute template.
- **`/iphone-script`**: Dedicated to Apple iPhone and iPad devices running iOS 18 / 17. Includes an iOS battery percentage status bar template.
- **`/gta6-script`**: Dedicated to Grand Theft Auto VI (GTA 6) and PlayStation 5 intact together. Combines the complete 8-tab in-game settings taxonomy of GTA 6 with PS5 console OS settings, featuring separate blueprints for GTA 6 gameplay/controller setup and PS5 console troubleshooting.

#### Core Architecture Highlights
- **3-Paragraph Intro System**:
  1. *Paragraph 1 (Short Hook)*: Immediate conversational hook stating the exact problem, symptom, or goal.
  2. *Paragraph 2 (Short & Concise Intro)*: 1-2 tight sentences stating the exact topic and what the video delivers.
  3. *Paragraph 3 (Short Transition)*: A snappy conversational bridge (*"So, let's get right into it!"*) leading directly into the live screen recording.
- **2-Part Clean Outro System**:
  1. *Paragraph 1 (Concise What Was Done)*: 1 punchy sentence summarizing the solution or setup achieved.
  2. *Paragraph 2 (Clean Sign Out)*: Professional YouTuber sign-off with engagement call-to-action (like, subscribe, comment).
- **Interactive Chat Selection**: Prompts the user via `ask_question` with tailored Intro and Outro options before generating the script.
- **Beginner-Friendly Point-and-Click**: Focuses on clear visual on-screen navigation rather than complex keyboard shortcuts or developer commands.
- **Natural Voiceover Rhythm**: Keeps actions concise (5-10 words per bullet point) with conversational transitional connectors.
- **Clean Formatting**: Formats UI click targets in bold and avoids quotation marks on bold targets.
- **Dedicated Device-Specific Templates**: Each skill folder includes a custom `template.docx` formatted around a real-world tutorial topic for that platform.

## Setup & Installation

### Antigravity Workspace
Copy any of the skill folders to `.agents/skills/` in your workspace directory:
```
.agents/skills/android-script/
.agents/skills/windows-script/
.agents/skills/mac-script/
.agents/skills/switch-script/
.agents/skills/ps5-script/
.agents/skills/iphone-script/
.agents/skills/gta6-script/
.agents/skills/tech-vid-script-v3/
```

### Global Installation
Place the folders in your global skills folder:
- Windows: `%USERPROFILE%\.gemini\antigravity\skills\`
- macOS/Linux: `~/.gemini/antigravity/skills/`

## License
MIT License.
