Extensions:
Core Python Support:
Python Microsoft Extension
Pylance Python Language Server
Python Debugger - debugging capabilities
Python Test Explorer - Visual Testing Interface

Code Quality Tools
Python DocString Generator
Python Path
Python Environment Manager
Python Snippets


Tooling:
uv - environment manager
ruff - python linter and formatter

Configuration:
- Python Interpreter
- Automatic Code Formatting - Black -  -> pip install black
        Config Cursor to use black:
        {
            "python.formatting.provider": "black",
            "editor.formatOnSave": true,
            "python.formatting.blackArgs": [
                "--line-length",
                "88"
            ]
        }

- Linting: Pylint to check for programming errors, enforce coding standards
    pip install pylint
    {
        "python.linting.enabled": true,
        "python.linting.pylintEnabled": true,
        "python.linting.lintOnSave": true
    }

- Type Checking - check for type errors: pip install mypy
    {
        "python.linting.mypyEnabled": true
    }
