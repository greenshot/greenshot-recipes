# Region Snip with Your Own Tool

A starting point for running a program of your own on a capture: it captures a region you select, runs a command with the
saved file, plays a sound and opens the result in the editor.

As shipped, the command only prints a line (`cmd.exe /c echo ...`), so it changes nothing; the line is in
`${var.tool.output}`. Replace `Program` and `Arguments` with the tool you use, e.g. ImageMagick to add a border
(`magick.exe`, `mogrify -border 20 "${export.file}"`), and set `Output` to `File`: the image is then read again from the
file the tool changed. Greenshot already writes optimized PNG files, an optimizer isn't needed.

## Use it

- Tray menu: **Snip & Run My Tool**
- Hotkey: Ctrl + Shift + O, change it in Settings > General

## Options

| Option | Default |
|---|---|
| Hotkey | Ctrl + Shift + O |

## Allows

Runs `cmd.exe`. Greenshot asks before the first run.
