# GitHub Folder Downloader

[![C++](https://img.shields.io/badge/Language-C%2B%2B-%23f34b7d.svg?style=plastic)](https://en.wikipedia.org/wiki/C%2B%2B)
   [![Windows](https://img.shields.io/badge/Platform-Windows-0078d7.svg?style=plastic)](https://en.wikipedia.org/wiki/Microsoft_Windows)
   [![x64](https://img.shields.io/badge/Arch-x64-red.svg?style=plastic)](https://en.wikipedia.org/wiki/X86-64)
   [![License](https://img.shields.io/github/license/R3nzTheCodeGOD/R3nzSkin.svg?style=plastic)](LICENSE)
   ![Windows](https://github.com/R3nzTheCodeGOD/R3nzSkin/workflows/Windows/badge.svg?branch=main&event=push)

A command line application (CLI) to download only a specific folder without downloading the full repository implemented with Python using Typer and GitHub API.

## Getting Started

<p align=left>
  <img src='https://img.shields.io/badge/11k-downloads-green'> | <img src='https://img.shields.io/badge/Windows-EXE-violet'> | <img src='https://img.shields.io/badge/%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%9C%B0-rating-yellow'>

<p align=center>
  
  | Update | Date | Link | Pin |
  |---------|-----------|--------|----------|
  | v 2.2 | December 11nd, 2023 | [Cl1ck](https://www.mediafire.com/folder/ce9hdxjzh344l/Github+DownloaderR) | r3nz 
</p>

- Any other way that allows you to install the package from PyPI.

## Commands

```bash
Usage: gh-folder-download [OPTIONS]

Options:
  --url TEXT                      Repository URL  [required]
  --output DIRECTORY              Output folder  [default: .]
  --token TEXT                    GitHub token
  --force / --no-force            Remove existing output folder if it exists
                                  [default: no-force]
  --install-completion [bash|zsh|fish|powershell|pwsh]
                                  Install completion for the specified shell.
  --show-completion [bash|zsh|fish|powershell|pwsh]
                                  Show completion for the specified shell, to
                                  copy it or customize the installation.
  --help                          Show this message and exit.
```

## GitHub Repository URL format

- `https://github.com/{user_or_organization}/{repository_name}`
  > Download the full repository from the default branch.
- `https://github.com/{user_or_organization}/{repository_name}/tree/{branch}`
  > Download the full repository from the specified branch.
- `https://github.com/{user_or_organization}/{repository_name}/tree/{branch}/{folder_path}`
  > Download the specified folder from the specified branch.
