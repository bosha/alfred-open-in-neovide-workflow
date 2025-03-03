# alfred-open-in-neovide-workflow

An Alfred 5 workflow to open files or folders in [Neovide](https://neovide.dev), a modern GUI for Neovim. This workflow is inspired by and adapted from the [alfred-open-with-vscode-workflow](https://github.com/alexchantastic/alfred-open-with-vscode-workflow), with a few customizations to better suit Neovide.

## Installation

1. [Download the workflow](https://github.com/bosha/alfred-open-in-neovide-workflow/releases/latest) from the [Releases](https://github.com/bosha/alfred-open-in-neovide-workflow/releases).
1. Double-click the downloaded `OpenInNeovide.alfredworkflow` file to import it into Alfred.
1. Customize the keywords if desired, then confirm the installation in Alfred.

## Usage

The workflow provides two default commands: `vide` and `videf`.

- `vide`: Use this command with an open and selected Finder window to launch Neovide in the current directory.
- `videf`: Use this command followed by a file or folder name to open a specific file or folder in Neovide.

## Configuration

The workflow includes several options to customize its behavior:

- The both `vide` and `videf` keywords can be changed in the workflow configuration.
- `Open in New Window` - controls whether Neovide opens a new window or reuses an existing one:
  - **Checked**: A new Neovide window will always be opened, regardless of whether an existing window is already open.
  - **Unchecked**: The workflow will attempt to reuse an existing Neovide window (if one is open).

## Requirements

- **Alfred 5** with the [Powerpack](https://www.alfredapp.com/powerpack/) enabled.
- **Neovide** installed on your system. If you haven’t installed it yet, you can find installation instructions on the [Neovide website](https://neovide.dev/).

## Troubleshooting

- Ensure Neovide is installed and accessible in your system’s PATH.
- If the workflow doesn’t work as expected, double-check the keywords and ensure they don’t conflict with other Alfred workflows.
