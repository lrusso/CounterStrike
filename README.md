# Counter Strike

Counter Strike running in the web browser using JavaScript and WebAssembly. Simply open the link below, click the red icon, and select the `ZIP` file that must contain the `valve` and `cstrike` folders; all files will be loaded and the game will start automatically.

![alt screenshot](https://lrusso.github.io/CounterStrike/SCREENSHOT.jpg)

## Website:

https://lrusso.github.io/CounterStrike/CounterStrike.htm

## Special keys:

| Action          | macOS Shortcut | Windows Shortcut | Safari Shortcut |
| :-------------- | :------------: | :--------------: | :-------------: |
| Fullscreen mode |  Command + F   |     Ctrl + F     |    Ctrl + F     |

## Main differences with the original project:

- Bots will be added automatically to the game.
- Adjusted the name server.
- Adjusted the UI resolution.
- Adjusted the default player name.
- Removed the CDN dependency (isolated client).
- Removed the module requirement from the script.
- Implemented a fullscreen mode during the gameplay.
- Implemented a ES5 unzip utility that doesn't require an import.
- Implemented a workaround that replaced ScriptProcessorNode (deprecated).

## Based on the work of:

https://github.com/modesage/cs1.6-browser
