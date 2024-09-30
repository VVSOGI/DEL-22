# Custom-Picture-in-Picture Chrome Extension

A simple Chrome Extension to demonstrate the [Picture-in-Picture Web API](https://wicg.github.io/picture-in-picture/) in Chrome.

Get it on the Chrome Web Store at https://chrome.google.com/webstore/detail/hkgfoiooedgoejojocmhlaklaeopbecg

<img src="https://raw.githubusercontent.com/beaufortfrancois/picture-in-picture-chrome-extension/master/screenshot.png">

## New in this custom release

The existing picture-in-picture-chrome-extension can only be switched on the tab where the initial video was played in PIP mode, but the custom-picture-in-picture-chrome-extension can switch PIP videos on other tabs using shortcuts.

## Configuration

The keyboard shortcut

```json
    "_execute_action": {
      "suggested_key": {
        "windows": "Alt+P",
        "mac": "Alt+P",
        "chromeos": "Alt+P",
        "linux": "Alt+P"
      }
    }, // default utils
    "switch": {
      "suggested_key": {
        "default": "Alt+Shift+1",
        "mac": "Command+Shift+1"
      },
      "description": "Test 1"
    } // New in this release
```

The keyboard shortcut can be changed on the
Chrome Extension Shortcuts settings page:
chrome://extensions/shortcuts

## How to use

1. git clone [this-repo]
2. move to url -> chrome://extensions/shortcuts
3. Turn on Developer mode in the upper-right corner.
4. Click button that Load the extracted extension in the upper-left corner.
5. Select the folder where your manifest.json is located
6. Use it as you would with the picture-in-picture-chrome-extension.
