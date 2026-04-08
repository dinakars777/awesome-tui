# awesome-tui [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🎨 A curated list of awesome TUI (Text User Interface) apps and frameworks

Terminal UIs are having a renaissance. Modern TUI frameworks make it easy to build beautiful, interactive applications that run in the terminal. This list collects the best TUI apps, frameworks, and resources.

## Contents

- [Why TUI?](#why-tui)
- [Frameworks](#frameworks)
- [Applications](#applications)
  - [Development Tools](#development-tools)
  - [Git & Version Control](#git--version-control)
  - [System Monitoring](#system-monitoring)
  - [Productivity](#productivity)
  - [File Management](#file-management)
  - [Databases](#databases)
  - [Networking](#networking)
  - [Media](#media)
  - [Games](#games)
  - [Fun](#fun)
- [Design Resources](#design-resources)
- [Tutorials & Guides](#tutorials--guides)
- [Contributing](#contributing)

## Why TUI?

**Advantages of TUI apps:**
- 🚀 Fast and lightweight
- 🔌 Works over SSH
- ⌨️ Keyboard-driven workflow
- 🎨 Beautiful and modern (not your grandpa's terminal)
- 🔋 Low resource usage
- 🌐 Cross-platform
- 📦 Easy to distribute

## Frameworks

Build your own TUI apps with these frameworks.

### Rust
- [Ratatui](https://github.com/ratatui-org/ratatui) - Rust library for building rich terminal UIs (successor to tui-rs)
- [Cursive](https://github.com/gyscos/cursive) - TUI library for Rust, inspired by ncurses
- [tui-realm](https://github.com/veeso/tui-realm) - Framework for Ratatui to build stateful apps

### Go
- [Bubble Tea](https://github.com/charmbracelet/bubbletea) - Powerful TUI framework based on Elm architecture
- [tview](https://github.com/rivo/tview) - Rich interactive widgets for terminal UIs
- [termui](https://github.com/gizak/termui) - Terminal dashboard library

### Python
- [Textual](https://github.com/Textualize/textual) - Modern TUI framework with CSS-like styling
- [Rich](https://github.com/Textualize/rich) - Beautiful terminal formatting and rendering
- [urwid](https://github.com/urwid/urwid) - Console user interface library
- [py-cui](https://github.com/jwlodek/py_cui) - Python library for creating CUI/TUI interfaces

### JavaScript/TypeScript
- [Ink](https://github.com/vadimdemedes/ink) - React for CLIs - build TUIs with React components
- [blessed](https://github.com/chjj/blessed) - High-level terminal interface library
- [terminal-kit](https://github.com/cronvel/terminal-kit) - Terminal utilities and TUI framework

### C/C++
- [FTXUI](https://github.com/ArthurSonzogni/FTXUI) - Functional Terminal UI library for C++
- [ncurses](https://invisible-island.net/ncurses/) - Classic terminal UI library
- [notcurses](https://github.com/dankamongmen/notcurses) - Modern ncurses alternative with multimedia support

### Other Languages
- [Charm](https://github.com/charmbracelet/charm) - Tools for building delightful TUIs (Go)
- [tui-rs](https://github.com/fdehau/tui-rs) - Original Rust TUI library (now Ratatui)
- [FINAL CUT](https://github.com/gansm/finalcut) - C++ library for creating terminal applications

## Applications

### Development Tools

- [lazygit](https://github.com/jesseduffield/lazygit) - Simple terminal UI for git commands
- [lazydocker](https://github.com/jesseduffield/lazydocker) - Terminal UI for Docker and Docker Compose
- [k9s](https://github.com/derailed/k9s) - Kubernetes CLI to manage clusters
- [gitui](https://github.com/extrawurst/gitui) - Blazing fast terminal UI for git
- [tig](https://github.com/jonas/tig) - Text-mode interface for git
- [gh-dash](https://github.com/dlvhdr/gh-dash) - GitHub dashboard in your terminal

### Git & Version Control

- [git-time-machine](https://github.com/dinakars777/git-time-machine) - Visual git reflog browser to undo mistakes
- [gitui](https://github.com/extrawurst/gitui) - Fast terminal UI for git written in Rust
- [lazygit](https://github.com/jesseduffield/lazygit) - Simple terminal UI for git commands
- [tig](https://github.com/jonas/tig) - Text-mode interface for git
- [grv](https://github.com/rgburke/grv) - Terminal interface for viewing git repositories

### System Monitoring

- [btop](https://github.com/aristocratos/btop) - Resource monitor with beautiful interface
- [htop](https://github.com/htop-dev/htop) - Interactive process viewer
- [bottom](https://github.com/ClementTsang/bottom) - Customizable cross-platform graphical process/system monitor
- [glances](https://github.com/nicolargo/glances) - Cross-platform system monitoring tool
- [zenith](https://github.com/bvaisvil/zenith) - Sort of like top or htop but with zoom-able charts
- [ytop](https://github.com/cjbassi/ytop) - TUI system monitor written in Rust

### Productivity

- [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) - Terminal UI for Taskwarrior
- [todo-tui](https://github.com/aome510/todo-tui) - Terminal UI for managing todo lists
- [jrnl](https://github.com/jrnl-org/jrnl) - Command-line journal application
- [calcurse](https://github.com/lfos/calcurse) - Calendar and scheduling application
- [visidata](https://github.com/saulpw/visidata) - Terminal spreadsheet multitool

### File Management

- [ranger](https://github.com/ranger/ranger) - Vim-inspired file manager
- [nnn](https://github.com/jarun/nnn) - Fast, feature-rich file manager
- [lf](https://github.com/gokcehan/lf) - Terminal file manager written in Go
- [yazi](https://github.com/sxyazi/yazi) - Blazing fast terminal file manager
- [broot](https://github.com/Canop/broot) - New way to navigate directories

### Databases

- [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocomplete
- [mycli](https://github.com/dbcli/mycli) - MySQL CLI with autocomplete
- [litecli](https://github.com/dbcli/litecli) - SQLite CLI with autocomplete
- [gobang](https://github.com/TaKO8Ki/gobang) - Cross-platform TUI database management tool
- [redis-tui](https://github.com/mylxsw/redis-tui) - Redis TUI client

### Networking

- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool
- [gping](https://github.com/orf/gping) - Ping with a graph
- [trippy](https://github.com/fujiapple852/trippy) - Network diagnostic tool
- [termshark](https://github.com/gcla/termshark) - Terminal UI for tshark (Wireshark)
- [dog](https://github.com/ogham/dog) - Command-line DNS client

### Media

- [spotify-tui](https://github.com/Rigellute/spotify-tui) - Spotify client for the terminal
- [ncspot](https://github.com/hrkfdn/ncspot) - Cross-platform ncurses Spotify client
- [musikcube](https://github.com/clangen/musikcube) - Cross-platform terminal-based music player
- [cmus](https://github.com/cmus/cmus) - Small, fast console music player
- [mpv](https://github.com/mpv-player/mpv) - Media player (has TUI mode)

### Games

- [tetris-tui](https://github.com/samtay/tetris) - Tetris in the terminal
- [snake-tui](https://github.com/lemnos/tt) - Terminal typing test
- [2048-tui](https://github.com/alewmoose/2048-in-terminal) - 2048 game in terminal
- [chess-tui](https://github.com/thomas-mauran/chess-tui) - Chess game in the terminal
- [minesweeper-tui](https://github.com/cpcloud/minesweeper-tui) - Minesweeper in the terminal

### Fun

- [cmatrix](https://github.com/abishekvashok/cmatrix) - Matrix-style terminal screensaver
- [asciiquarium](https://github.com/cmatsuoka/asciiquarium) - Aquarium animation in ASCII art
- [moody](https://github.com/dinakars777/moody) - Your MacBook has feelings - hardware events trigger personality responses
- [sl](https://github.com/mtoyoda/sl) - Steam locomotive runs across your terminal
- [cowsay](https://github.com/piuccio/cowsay) - Configurable talking cow
- [fortune](https://github.com/shlomif/fortune-mod) - Random quotes and sayings

## Design Resources

### Color Schemes
- [Catppuccin](https://github.com/catppuccin/catppuccin) - Soothing pastel theme for TUIs
- [Dracula](https://github.com/dracula/dracula-theme) - Dark theme for many applications
- [Nord](https://github.com/nordtheme/nord) - Arctic, north-bluish color palette
- [Gruvbox](https://github.com/morhetz/gruvbox) - Retro groove color scheme

### Icons & Symbols
- [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Iconic font aggregator with glyphs
- [Unicode Box Drawing](https://en.wikipedia.org/wiki/Box-drawing_character) - Characters for drawing boxes

### Design Patterns
- [Charm Design System](https://github.com/charmbracelet/lipgloss) - Style definitions for TUIs
- [TUI Design Principles](https://github.com/rothgar/awesome-tuis) - Best practices for TUI design

## Tutorials & Guides

### Getting Started
- [Building TUIs with Ratatui](https://ratatui.rs/tutorials/) - Official Ratatui tutorials
- [Bubble Tea Tutorial](https://github.com/charmbracelet/bubbletea/tree/master/tutorials) - Learn Bubble Tea framework
- [Textual Tutorial](https://textual.textualize.io/tutorial/) - Build your first Textual app

### Advanced Topics
- [TUI Performance Optimization](https://ratatui.rs/concepts/performance/) - Make your TUI fast
- [Handling Terminal Events](https://docs.rs/crossterm/latest/crossterm/event/) - Keyboard, mouse, resize events
- [Terminal Capabilities](https://invisible-island.net/ncurses/ncurses.faq.html) - Understanding terminal features

### Video Tutorials
- [Building a TUI in Rust](https://www.youtube.com/results?search_query=ratatui+tutorial) - YouTube tutorials
- [Charm CLI Tools](https://www.youtube.com/c/CharmCLI) - Charm's YouTube channel

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

### How to Contribute

1. **Add a TUI app**: Submit a PR with your favorite TUI application
2. **Add a framework**: Know a great TUI framework? Share it!
3. **Improve descriptions**: Make existing entries more helpful
4. **Fix issues**: Help improve the list

### Contribution Guidelines

- Apps should be actively maintained (updated in last 2 years)
- Include a brief description of what the app does
- Add to the appropriate category
- Keep descriptions concise (1-2 sentences)
- Check for duplicates before adding

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, contributors have waived all copyright and related rights to this work.

---

**Star this repo** if you love TUIs! ⭐

**Follow for updates** as we discover more awesome terminal applications.
