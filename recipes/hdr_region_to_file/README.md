# HDR region to file

Select a region on the live screen of an HDR display and save it as an HDR file: JPEG XR, lossless, with the
highlights as they were on the screen. JPEG XR is built into Windows and is the format the Xbox Game Bar uses for HDR
screenshots.

The region is selected on the live screen, so an HDR video keeps playing while you select.

Without HDR content a normal PNG is saved, and the notification says so. That happens when the region is on an SDR
display, or when nothing in it is brighter than SDR white or has colors outside sRGB (for example a normal window).

## Use it

- Hotkey: Ctrl + Shift + PrintScreen, change it in the recipe's settings
- Right-click context menu

## Options

| Option | Default |
|---|---|
| Hotkey | Ctrl + Shift + PrintScreen |
| Ask where to save the HDR file | off: saves to your output folder |
| Open in the editor instead | off: draw on the capture, then Save as JPEG XR keeps the highlights with your drawing on top |
| Ask how to save an HDR capture | off: with HDR content, asks whether to save it as HDR file (JPEG XR) or PNG |

## Allows

Writes the file to your output folder, or where you choose.
