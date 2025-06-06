# Demo Dotfiles

This repository contains example shell aliases and functions for demonstration purposes.
It complements the blog article:
[https://yanickvanweydeveldt.com/shell-aliases-guide](https://yanickvanweydeveldt.com/shell-aliases-guide)

**Disclaimer**: These configurations are provided as-is, without any warranty. Use at your own risk.

## Purpose

Provide clear and concise examples of shell customisations.

## Contents

- `.aliases` — General-purpose shell aliases
- `.aliases-linux` — Linux-specific aliases
- `.aliases-macos` — macOS-specific aliases
- `.functions` — General-purpose shell functions
- `.functions-linux` — Linux-specific functions
- `.functions-macos` — macOS-specific functions

## Usage

Source the relevant files from your shell configuration (`.bashrc`, `.zshrc`):

```bash
source ~/path/to/.aliases
source ~/path/to/.functions
```

## Compatibility

- Verified on **macOS** using **Zsh**
- Verified on **Ubuntu Linux** using **Bash**

Platform-specific entries are conditionally loaded based on the detected environment.

## Safety Notes

- These aliases and functions are safe to use and share. They do not contain any sensitive information. However, always exercise caution when executing scripts fetched directly from the internet (e.g. via `curl | python3`).

- Replace `<user>:<group>` with the correct ownership values for your system. Adjust variables such as `PHP_VER` and `SITE_DIR` as required. Always use caution with commands like `rm -rf` and ensure paths are correctly set to avoid accidental data loss.

## License

This repository is licensed under the [MIT License](LICENSE).
