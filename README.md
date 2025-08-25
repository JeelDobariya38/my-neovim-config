# My Neovim Config

## Getting Started

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
