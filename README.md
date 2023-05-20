# Fedora PC Setup

This Ansible playbook automates the installation and setup of the packages and configurations I use on Fedora.

## Packages Installed

- [Brave Browser](https://brave.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Docker CE](https://docs.docker.com/engine/install/)
- [Alacritty](https://github.com/alacritty/alacritty)
- [Fish Shell](https://fishshell.com/)
- [Neovim](https://neovim.io/)
- [Git Delta](https://github.com/dandavison/delta)
- [Duf](https://github.com/muesli/duf)
- [Foliate](https://johnfactotum.github.io/foliate/)
- [Pop Shell](https://github.com/pop-os/shell)

## GNOME Extensions Installed

- [Vitals](https://extensions.gnome.org/extension/1460/vitals/)
- [No Topleft Hot Corner](https://extensions.gnome.org/extension/118/no-topleft-hot-corner/)
- [Sp-Tray](https://extensions.gnome.org/extension/358/sp-tray/)
- [Spotify Controller](https://extensions.gnome.org/extension/55/media-player-indicator/)
- [Custom Accent Colors](https://extensions.gnome.org/extension/1465/custom-accent-colors/)
- [User Themes](https://extensions.gnome.org/extension/19/user-themes/)
- [Background Logo](https://extensions.gnome.org/extension/208/background-logo/)
- [AppIndicator Support](https://extensions.gnome.org/extension/615/appindicator-support/)
- [Pop Shell](https://extensions.gnome.org/extension/1160/pop-shell/)

## Screenshots

Here are some screenshots of the Fedora PC setup:

![Screenshot 1](screenshots/screenshot1.png?raw=true)

## Usage

1. Clone the repository: `git clone https://github.com/yourusername/your-repo.git`
2. Install Ansible: `sudo dnf install ansible`
3. Customize the playbook file `setup.yml` with your desired configurations.
4. Run the playbook: `ansible-playbook setup.yml -K`
5. Open debug log using: `nc -lk 4343`

## TODO
- [ ] Install GNOME shell extensions without a prompt.
- [ ] Error handling (port for netcat, missing permissions, etc.)
