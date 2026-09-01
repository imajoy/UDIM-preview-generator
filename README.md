[Copyright](LICENSE.md) © 2026 **Ajoy Pal**

All Rights Reserved.

# UDIM Preview Generator for Maya

![Maya](https://img.shields.io/badge/Autodesk%20Maya-2018%2B-blue)
![Python](https://img.shields.io/badge/Python-PySide2%20%2F%20PySide6-blue)
![License](https://img.shields.io/badge/License-Proprietary-red)

<p align="center">
  <img src="Images/udim-preview-generator.png" alt="UDIM Preview Generator" width="800">
</p>

**UDIM Preview Generator for Maya** is a one-click tool for generating preview textures for UDIM-based texture workflows inside Autodesk Maya.

The tool automatically finds UDIM texture nodes in the current Maya scene and generates preview textures without requiring manual selection of texture nodes.

> **Commercial Tool**
>
> The complete software package is available through Gumroad.
> This GitHub repository contains product information, documentation, and installation information only.
>
> The full source code and commercial tool package are not included in this repository.

### 🛒 Purchase

**[Buy UDIM Preview Generator for Maya on Gumroad](https://ajoyp.gumroad.com/l/zoqsmd)**

---

## Features

### One-Click UDIM Preview Generation

Generate previews for all UDIM textures in your Maya scene with a single click.

### Automatic UDIM Detection

The tool automatically searches the Maya scene for UDIM texture nodes.

No need to manually select texture nodes one by one.

### Preview Quality

Choose the preview quality according to your workflow:

- Low
- Medium
- High

High-quality preview generation supports:

- 2K
- 4K
- 8K

### Zero Manual Setup

No repetitive texture-node selection or manual texture-node opening is required.

### Simple Dark-Themed Interface

A clean and simple interface designed for a fast Maya workflow.

### Maya Version Support

Designed to work with:

- Maya 2018+
- PySide2
- PySide6

---

## Installation

The complete tool is available through Gumroad.

After downloading the tool, make sure the provided Python module is available in Maya's Python path.

Open the **Python Script Editor** in Maya and run:

```python
import importlib
import udim_preview_tool

importlib.reload(udim_preview_tool)

udim_preview_tool.show_window()
