# Tkinter Stubs

This is a package with type annotation stubs for the Tkinter module(s) built from <https://github.com/python/typeshed>. Made for a convenient development of a code which uses Tkinter.

For now (until I deploy it on pypi.org), the package can be installed from releases with the following command:
```
pip install https://github.com/insolor/tkinter-stubs/releases/download/0.1.0/tkinter_stubs-0.1.0-py3-none-any.whl
```
Also you can add it to requirements.txt like this (some old versions of pip don't support such syntax, so I recommend updating pip):
```
tkinter-stubs @ https://github.com/insolor/tkinter-stubs/releases/download/0.1.0/tkinter_stubs-0.1.0-py3-none-any.whl
```
Or to pyproject.toml:
```toml
[tool.poetry.dev-dependencies]
tkinter-stubs = { url = "https://github.com/insolor/tkinter-stubs/releases/download/0.1.0/tkinter_stubs-0.1.0-py3-none-any.whl" }
```
