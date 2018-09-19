# Installation

1. Install [Python](https://www.python.org/downloads/).
2. `python -m pip install pylint autopep8` (Linter)
3. `python -m pip install autopep8` (Autoformatter)
4. Install python extension: `ext install ms-python.python`
5. Press <kbd>Shift + Alt + F</kbd> to check formatting works.

# Troubleshooting

+ If installation fails on windows, use an elevated Command Prompt.
	+ Also, check your Python version: `python --version`
+ VS Code cannot find globally installed pylint, autopep8 in virtual enviroment.
	+ Related: https://github.com/Microsoft/vscode-python/issues/409
	+ Fix `settings.json`
		+ "python.linting.pylintPath": `YOUR_PYTHON\Scripts\pylint`
		+ "python.formatting.autopep8Path": `YOUR_PYTHON\Scripts\autopep8`
