# Installation

1. Install [DMD](https://dlang.org/download.html) and setenv path.
2. Install code-d: `ext install webfreak.code-d`
3. Set `d.stdlibPath` to appropriate path.
	+ If you don't know what to write on, copy default values and modify it.

# Troubleshooting

+ You need to install **DMD** on Windows. Otherwise, it can stuck. No LDC!
+ If the extension doesn't work, simply remove it, delete files and reinstall.
	+ Linux: `~/.vscode/code-d/`, `~/.local/share/code-d/`
	+ Windows: `%USERPROFILE%/.vscode/code-d/`, `%USERPROFILE%/AppData/Roaming/code-d/`
