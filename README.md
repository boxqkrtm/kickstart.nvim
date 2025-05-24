# kickstart.nvim

## External Requirements
- Basic utils: `git`, `make`, `unzip`, C Compiler (`gcc`)
- [ripgrep](https://github.com/BurntSushi/ripgrep#installation)
- Clipboard tool (xclip/xsel/win32yank...)
- [Nerd Font](https://www.nerdfonts.com/) (optional)
- Language tools (npm, go, etc. - if needed)

## Installation

**Recommended:** Fork this repository and clone your fork.

### Clone Command

**Linux and macOS:**

```sh
git clone [https://github.com/](https://github.com/)<your_github_username>/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

**Windows (cmd.exe):**

```
git clone [https://github.com/](https://github.com/)<your_github_username>/kickstart.nvim.git "%localappdata%\nvim"
```

**Windows (powershell.exe):**

```powershell
git clone [https://github.com/](https://github.com/)<your_github_username>/kickstart.nvim.git "${env:LOCALAPPDATA}\nvim"
```

### Install Dependencies (Example for Arch Linux)

```sh
sudo pacman -S --noconfirm --needed gcc make git ripgrep fd unzip neovim
```
