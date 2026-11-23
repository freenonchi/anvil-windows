# Anvil for Windows

A coding agent for your own projects: it reads and edits code, runs commands and tests, and shows you every change as a diff before it lands. It works with almost any model, from free Gemini keys to local Ollama.

This is a Windows port of [Anvil](https://github.com/deeeeone/Anvil) by deeeeone, which was made for macOS.

## Download

Get the latest setup file from the [Releases page](https://github.com/freenonchi/anvil-windows/releases/latest) and run it.

- Windows 10 or later. WebView2 is included in Windows 11 and installed on most Windows 10 machines.
- It installs for your user only, with no administrator prompt.
- The installer is not code-signed yet, so Windows may show "Windows protected your PC". Choose **More info**, then **Run anyway**.

## Updates

Anvil checks this page when it starts and every few hours. If a newer version exists, a banner asks whether you want it. Say yes and it downloads the update, checks its signature and installs it. Nothing happens without your click, and it waits while the agent is working. You can turn the check off in Settings, About.

## Your data

Settings and sessions live in `%APPDATA%\Anvil`, outside the install folder, so updating or uninstalling never touches them. API keys are kept in Windows Credential Manager. Before the first launch of a new version, Anvil copies your settings and sessions into a `backups` folder there and keeps the last three copies.

## Credits

Anvil for Windows is a port of [Anvil](https://github.com/deeeeone/Anvil) by deeeeone. The original design, the agent protocol and the way it works are theirs. The credits are also inside the app, in the Credits button above Settings.

The source code is private.

## Problems

Open an issue on this repository.
