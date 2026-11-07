# Region Snip with External Tool Optimization

A starting point for running your own tool on a capture: it captures a region you select, runs a command with the
saved file, plays a sound and opens the result in the editor.

As shipped, the command only prints a line (`cmd.exe /c echo ...`), so it changes nothing; the line is in
`${var.optimizer.output}`. Replace `Program` and `Arguments` with the optimizer you use, e.g. `pngquant.exe` or
`oxipng.exe`, and set `Output` to `File`: the image is then read again from the file the optimizer changed.

## Use it

- Tray menu: **Snip & Optimize Image**
- Hotkey: Ctrl + Shift + O, change it in Settings > General

## Options

| Option | Default |
|---|---|
| Hotkey | Ctrl + Shift + O |

## Allows

Runs `cmd.exe`. Greenshot asks before the first run.
