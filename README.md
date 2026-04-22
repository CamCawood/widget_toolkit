# Widget Toolkit

A lightweight Python utility for building **Tkinter** and **CustomTkinter** user interfaces with cleaner, reusable code.

Instead of repeatedly configuring widgets, `Widget Toolkit` provides a structured way to create and place UI components with sensible defaults.

---

## Features

- ✅ Supports **Tkinter** and **CustomTkinter**
- ✅ Reduces repetitive UI code
- ✅ Built-in default values (fonts, sizes, colours)
- ✅ Centralised widget creation logic
- ✅ Grid-based layout handled automatically
- ✅ Easy to reuse across multiple projects

---

## Widgets Included

### CustomTkinter
- `CTkLabel`
- `CTkButton`
- `CTkComboBox`
- `CTkFrame`
- `CTkTextbox`
- `CTkScrollableFrame`
- `CTkEntry`

### Tkinter
- `Listbox`
- `Toplevel`
- `Spinbox`
- `Entry`

---

## How It Works

The toolkit is built around two core classes:

### `ConfigureWidgetValues`
Handles default values and fallbacks:
- Font handling
- Width / height defaults
- Colours
- Grid positioning
- Spinbox ranges

### `CreateWidgets`
Provides methods to:
- Create widgets
- Apply defaults automatically
- Place them using `.grid()`

---

## Installation

```bash
git clone https://github.com/your-username/widget_toolkit.git
cd widget_toolkit
pip install customtkinter
