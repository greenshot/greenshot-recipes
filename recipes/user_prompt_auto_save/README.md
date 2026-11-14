# Region with automatic save

Captures a region you select and asks what to do with it. If you don't choose within a few seconds, the capture is
saved automatically as PNG into a folder with today's date, e.g. `Pictures\Greenshot_Autosave\2026-11-14\2026-11-14-09-30-12 Title.png`.

The prompt shows a preview and three choices:

- **Save automatically (default)**: saves into the automatic folder; Enter or waiting until the countdown ends does the same
- **Save As**: opens the save dialog in the Save As folder
- **Editor (Esc)**: opens the capture in Greenshot's editor, nothing is saved

## Use it

- Hotkey: Ctrl + Alt + A, change it in Greenshot's Settings > General (hotkeys) or in the recipe editor
- Tray menu: **Region with automatic save**

## Options

| Option | Default |
|---|---|
| Hotkey | Ctrl + Alt + A |
| Folder for automatic saving | `Pictures\Greenshot_Autosave` (one subfolder per day) |
| Folder for Save As | `Pictures\Greenshot_Manualsave` |
| Seconds until automatic save | 3 |

An existing file is never overwritten: automatic saving adds a number, Save As asks.

## Allows

Writes PNG files into the two folders above (the daily subfolder is created when needed).
