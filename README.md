[```
# ⚡ Somtocode Dotfiles | Arch Linux + KDE Plasma Development Setup

Welcome to my official dotfiles repository! This is my daily-driver setup running **Arch Linux** with **KDE Plasma**, tailored for full-stack web development (Python &amp; JavaScript) and a clean, aesthetic desktop workflow [1, 2].

&gt; 📺 **Watch the full setup video on YouTube**: [Arch Linux + KDE Plasma Development Setup](https://www.youtube.com/watch?v=kL5ynjOyh6s)

---

## 🖼️ Desktop Preview

![Desktop Screenshot](./screenshots/desktop.png)
*(Replace this image with a screenshot of your desktop setup!)*

---

## ⚙️ System Specs &amp; Theme Details

| Component | Choice / Setting |
| :--- | :--- |
| **OS** | Arch Linux [1] |
| **Desktop Environment** | KDE Plasma [1] |
| **Global Theme** | Catppuccin Mocha [2, 3, 5] |
| **Wallpaper** | Luffy Minimalist Background (sourced via WallHaven) [2, 5] |
| **UI Font** | Inter (System Interface) [6] |
| **Terminal Font** | JetBrains Mono Nerd Font (Size 11) [4, 7] |
| **Window Effects** | Wobbly/Bouncing animations &amp; hold-transparency [2] |
| **Terminal Fetch** | Fastfetch (`~/.config/fastfetch/config.jsonc`) [8, 9] |
| **Code Editor** | VS Code (Full-Stack Setup) [1, 2] |

---

## 📂 Repository Structure

```text
stc-dotfiles/
├── kde/
│   ├── kdeglobals                           # Plasma colors &amp; global palette settings [3, 10]
│   ├── kwinrc                               # Window decorations &amp; wobbly animation effects [2, 11]
│   ├── plasma-org.kde.plasma.desktop-appletsrc # Taskbar panel layout &amp; widget configs [6, 12]
│   └── kglobalshortcutsrc                   # Custom system keybindings
├── fastfetch/
│   └── config.jsonc                         # Custom Fastfetch layout [8, 9]
├── screenshots/
│   └── desktop.png                          # Setup preview image
└── README.md

```

---](https://notebook.google.com/notebook/05bf9251-07d0-431d-8afa-77d4846c7ddc)

## 🚀 Installation &amp; Setup

### 1\. Clone the Repository

```
git clone https://github.com/SomtocodeYT/stc-dotfiles.git ~/dotfiles
cd ~/dotfiles

```

### 2\. Back Up Your Existing Configs

&gt; ⚠️ **Important**: Always create a backup of your current settings before applying new dotfiles!

```
mkdir -p ~/.config/backup
cp -r ~/.config/kdeglobals ~/.config/kwinrc ~/.config/fastfetch ~/.config/backup/

```

### 3\. Apply the Configurations

Copy the configuration files into your local `~/.config/` directory:

```
# Apply KDE Plasma settings
cp -r kde/* ~/.config/

# Apply Fastfetch preset
mkdir -p ~/.config/fastfetch
cp fastfetch/config.jsonc ~/.config/fastfetch/config.jsonc

```

### 4\. Apply Changes

Log out and back into your KDE Plasma session to load all window animations and color schemes.

---

## 🛠️ Full-Stack Development Workflow

* **Primary Stack**: Python, JavaScript, HTML/CSS[1]
* **Editor**: VS Code[1][2]
* **Version Control**: Git &amp; GitHub[1]
* **Terminal**: Konsole / Foot running JetBrains Mono Nerd Font

---

## 💬 Connect &amp; Support

* 🎥 **YouTube Channel**: [@Somtocode](https://www.google.com/url?sa=E&amp;q=https%3A%2F%2Fwww.youtube.com%2F%40Somtocode)
* ⭐️ **Drop a star** on this repository if you found these dotfiles helpful!

---

*Created with ❤️ by Francis / Somto (Somtocode)*
