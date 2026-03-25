vaibhav@archlinux — Terminal Portfolio v3.0
A fully interactive, browser-based terminal portfolio that looks and feels like a real Arch Linux + Hyprland setup.
🚀 Quick Start
Just open index.html in any modern browser. No build step, no dependencies, no server needed.
# clone or download, then:
open index.html
# or
firefox index.html
✨ Features
Core Terminal
Feature
Description
Splash screen
Neofetch-style boot card with real Arch logo
Boot sequence
Animated systemd-style boot with [OK] / [START] / [WARN] lines
Waybar
Live clock, CPU %, RAM — updates every 5 seconds
Multi-tab
+ button or Ctrl+T to open new tabs, Ctrl+W to close
Command history
↑ ↓ arrows to navigate previous commands
Tab autocomplete
Tab key completes any command
Ctrl+L
Clear terminal (also works with clear)
Portfolio Commands
neofetch          Real Arch Linux ASCII logo + full system info
fastfetch         Larger Arch logo, fastfetch-style layout
about             Who is Vaibhav?
skills            Full tech stack
projects          12+ portfolio projects
experience        Work & education timeline
education         Coursework breakdown
certifications    Interests & what I'm learning
contact           Email, GitHub, LinkedIn
Fun / Easter Eggs
anime             Fullscreen braille anime girl overlay
pipes             Pipes screensaver (click to exit)
pokemon [name]    ASCII Pokémon art — 8 available
cowsay <text>     ASCII cow (try: cowsay amogus)
figlet <text>     Big block letter text
fortune           Random programmer wisdom via cowsay
matrix            FULLSCREEN green Matrix rain (click to exit)
sl                🚂 Train animation (classic sl easter egg)
System Commands
htop              Visual CPU/RAM bars + process table
theme             6-theme color picker (see Themes below)
ls / ls -la       File listing with colors
uname -a          Kernel info
git log/status    Fake git output
whoami / id       User info
echo <text>       Echo text
pwd               Print working directory
cat <file>        Read a file
sudo <cmd>        Prompts for password then runs
*.sh              Any .sh file runs a fake boot script
pacman/yay/paru   Package manager easter egg
Misspell Detection
Type a misspelled command (e.g. neoetch, fastech, anme) and the terminal will:
Show command not found
Suggest the correct command
Trigger the 🚂 sl train animation across the screen
🎨 Themes
Open the theme picker with the theme command or the sidebar button. Six themes included:
Theme
Based On
Tokyo Night (default)
Tokyo Night for Neovim
Catppuccin Mocha
Catppuccin color palette
Dracula
Dracula theme
Gruvbox Dark
Gruvbox retro palette
Nord
Nord arctic palette
One Dark
Atom One Dark
Themes apply live across the entire terminal — no reload needed.
⌨️ Keyboard Shortcuts
Shortcut
Action
Enter
Run command
↑ / ↓
Navigate command history
Tab
Autocomplete command
Ctrl+T
Open new tab
Ctrl+W
Close current tab
Ctrl+L
Clear terminal output
📁 File Structure
index.html          Everything — single self-contained file
README.md           This file
All logic, styles, and assets are embedded in index.html. No external dependencies except Google Fonts (loaded via CDN).
🛠 Tech Stack
Vanilla HTML / CSS / JavaScript — zero frameworks, zero build tools
Canvas API — matrix rain (background + fullscreen), pipes screensaver
CSS custom properties — live theme switching
Google Fonts — JetBrains Mono, Orbitron
Tokyo Night color scheme (default)
🐧 About
Built by Vaibhav Anil Badade — Aspiring AI Engineer · Full-Stack Dev · Game Dev
Diploma in Computer Engineering @ Vidyalankar Polytechnic, Mumbai (2024–2027)
📧 vaibhavbb83@gmail.com
🐙 github.com/Vaibhavbde
💼 linkedin/vaibhav-badade
I use Arch btw 🐧

