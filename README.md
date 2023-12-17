# Ola's - Oh My Posh Themes 🚀

Welcome to my dynamic collection of Oh My Posh themes! 🎨 Spice up your command-line interface on Linux, Mac, and Windows with these engaging themes.

## 🛠️ Installation

First, clone this repository to a local directory of your choice:

```shell
git clone https://github.com/OlaHulleberg/oh-my-posh-themes.git <your-directory>
```

### Setting Up the Theme

Add the appropriate initialization line to your shell profile script, and replace `<your-directory>` with the path to the cloned repository and `<theme>` with the theme filename.

#### Windows

Update your PowerShell profile (`Microsoft.PowerShell_profile.ps1`)
Can also be found by running echoing `$PROFILE`:

```powershell
oh-my-posh --init --shell pwsh --config <your-directory>/<theme>.omp.json | Invoke-Expression
```

#### For Linux & Mac

Edit your `~/.zshrc` | `~/.bashrc` | `~/.profile` | `~/.bash_profile`:

```bash
eval "$(oh-my-posh init <zsh|bash> --config <your-directory>/<theme>.omp.json)"
```

## 🎉 Theme Gallery

### 1. Ola 2023 🌟

A modern theme with a blend of dark grey and red.

![Ola 2023](assets/ola_2023-omp.png)

```
ola_2023.omp.json
```

## 💡 Tips & Tricks

- 🔄 Easily switch themes by updating the filename in your profile script.
- 🛠️ Personalize themes by tweaking their `.omp.json` files.

## 🤝 Contributing

Got a cool theme idea? Contributions are always welcome! Check [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📬 Feedback

Have suggestions or feedback? Feel free to open an issue or pull request.

Enjoy your command-line adventures! 🎉👩‍💻👨‍💻
