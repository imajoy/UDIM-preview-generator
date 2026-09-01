# Installation

## Requirements

- Autodesk Maya 2018 or later
- Supported Maya Python environment
- PySide2 or PySide6 depending on the Maya version

## Installation

Purchase and download the complete tool from Gumroad.

Place the provided tool files where Maya can access them.

## Launching the Tool

Open Maya's Python Script Editor and run:

```python
import importlib
import udim_preview_tool

importlib.reload(udim_preview_tool)

udim_preview_tool.show_window()
