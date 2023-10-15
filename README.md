# PyQt5 boilerplate

This is boilerplate code for PyQt5

## Usage

1. Clone this repository
2. Open `ui/mainwindow.py` with Qt Designer and modify it to your liking
3. If needed, [define slots](NOTES.md#slots) in `__main__.py`

## FAQ

### Why PyQt and not PySide?

I personnally prefer it because it allows to define slots more easily when loading ui files directly from the code.

### Alright, but why not use the uic to generate Python code?

I prefer to load ui files directly so that there are no build steps prior to running the code. It makes it way easier in IDE, where the play button becomes sufficient.
