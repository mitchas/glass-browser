![N|Solid](https://github.com/mitchas/glass-browser/raw/master/assets/icon64.png)
# **Glass Browser**
### [Downloads](https://github.com/mitchas/glass-browser/tree/master/releases)

A floating transparent browser for Windows.
  - Stays on top of other programs and apps.
  - Adjust transparency.
  - Click-through mode that ignores clicks and lets you interact with apps behind.

![N|Solid](https://github.com/mitchas/glass-browser/raw/master/assets/screenshot.PNG)


## Building & running it locally:
- Clone the repo.
- cd to the directory
- make sure electron is installed `npm install electron`
- install and run with `npm install && npm start`

## Packaging it (.app for mac, .exe for windows, or for linux ** Untested on Mac and Linux)
- Install [Electron Packager Interactive](https://github.com/Urucas/electron-packager-interactive) with `npm install -g electron-packager-interactive`
- run `epi`
- Follow steps
  - Icon is `./assets/icon.ico'

## Using it
- Enter a URL and hit >Enter
- Resize and position the window where you want it.
- Adjust transparency to your liking.
- Click the eye to enable click-through mode. It will ignore mouse clicks and let you interact with windows below.
- To disable click-through and interact with the window again, click the icon in the Windows dock/taskbar and minimize it, then click again to open it and it will be disabled.

## Known Issues
- Transparency seems to not be working on Linux - but it still floats above other windows.
