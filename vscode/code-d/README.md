# Installation

If you are new at D, install DMD. However, LDC works well too.

It does not support single file. You need to create a dub project. However, there was a [funding](https://dlang.org/blog/2018/07/13/funding-code-d/) for it, so it will be added soon.

## DMD

1. Install [DMD](https://dlang.org/download.html) and set enviroment variables. (PATH)
	+ Check `dmd`, `dub` is working properly.
2. Install code-d: `ext install webfreak.code-d`
3. Set `d.stdlibPath` to appropriate path. (Check default values)
	+ Windows: `%DMD_PATH%\druntime\import`, `%DMD_PATH%\src\phobos`

## LDC

1. Install [LDC](https://github.com/ldc-developers/ldc) and set enviroment variables. (PATH)
	+ Check `ldmd2`, `dub` is working properly.
2. Install code-d: `ext install webfreak.code-d`
3. Set `d.stdlibPath` to apporiate path.
	+ Windows: `%LDC_PATH%\import`
4. Set `d.dmdPath` to `ldmd2` (or other path you want to use).

You don't need to touch `d.servedPath` or other settings.

## dfmt and D-Scanner

1. Install [dfmt](https://github.com/dlang-community/dfmt).
2. Install [D-Scanner](https://github.com/dlang-community/D-Scanner).
3. Set enviroment variables. (PATH)

However, these are included in workspace-d.

# Troubleshooting

+ If the extension doesn't work, simply remove it, delete files and reinstall.
	+ Linux: `~/.vscode/code-d/`, `~/.local/share/code-d/`
	+ Windows: `%USERPROFILE%/.vscode/code-d/`, `%USERPROFILE%/AppData/Roaming/code-d/`
