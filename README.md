
# kickstart.nvim

## External Requirements

* Basic utilities: `git`, `make`, `unzip`, C Compiler (`gcc`)

* [ripgrep](https://github.com/BurntSushi/ripgrep#installation)

* Clipboard tool (e.g., xclip, xsel, win32yank)

* A [Nerd Font](https://www.nerdfonts.com/) (optional, for icons)

* Language-specific tools (e.g., `npm` for TypeScript, `go` for Golang)

## Installation

**Recommended Step:** Fork the `kickstart.nvim` repository to your own GitHub account.

### Clone Command

**Linux and macOS:**

```sh
git clone https://github.com/boxqkrtm/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

**Windows (cmd.exe):**

```
git clone (https://github.com/boxqkrtm/kickstart.nvim.git "%localappdata%\nvim"
```

**Windows (powershell.exe):**

```powershell
git clone https://github.com/boxqkrtm/kickstart.nvim.git "${env:LOCALAPPDATA}\nvim"
```

### Example Dependency Installation (Arch Linux)

```sh
sudo pacman -S --noconfirm --needed gcc make git ripgrep fd unzip neovim
```
