# My Neovim Config

## Getting Started (Installation)

### Prerequisites

Neovim: [Install](https://github.com/neovim/neovim/blob/master/INSTALL.md)

### Windows

```powershell
winget install Neovim.Neovim
```

```powershell
git clone "https://github.com/JeelDobariya38/my-neovim-config.git" "$env:LOCALAPPDATA\nvim"

Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
```

```powershell
nvim
```

### Linux/MacOS

```bash
brew install neovim
```

```bash
git clone "https://github.com/JeelDobariya38/my-neovim-config.git" ~/.config/nvim

rm -rf ~/.config/nvim/.git
```

```bash
nvim
```

## Updateing

### Windows

```powershell
Remove-Item $env:LOCALAPPDATA\nvim -Recurse -Force

git clone "https://github.com/JeelDobariya38/my-neovim-config.git" "$env:LOCALAPPDATA\nvim"
```

### Linux/MacOS

```bash
rm -rf ~/.config/nvim

git clone "https://github.com/JeelDobariya38/my-neovim-config.git" ~/.config/nvim
```
