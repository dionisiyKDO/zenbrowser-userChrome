# ZenBrowser UserChrome Customization

This repository contains my custom Firefox `userChrome.css` and related files, which modify the browser's user interface. 
The `style.css` file is based on a theme created by [@itsmefen[(https://github.com/itsmefen) - [Dark Harmony](https://github.com/itsmefen/Dark-Harmony). I've adapted it to suit my preferences.

## Contents
- `userChrome.css`: Ties together `context-menu.css` and `style.css`.
- `context-menu.css`: Customizes the right-click context menu.
- `style.css`: Theme and UI changes (adapted from [Dark Harmony](https://github.com/itsmefen/Dark-Harmony)).

## How to Use
1. Clone this repository.
2. Enable Firefox's custom CSS support:
   - Go to `about:config` in Firefox.
   - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
   - Set it to `true`.
3. Copy all `.css` files to your Firefox profile folder:
   - **Windows**: `C:\Users\<YourUsername>\AppData\Roaming\Mozilla\Firefox\Profiles\<YourProfile>\chrome\`
   - **macOS**: `~/Library/Application Support/Firefox/Profiles/<YourProfile>/chrome/`
   - **Linux**: `~/.mozilla/firefox/<YourProfile>/chrome/`
4. Restart Firefox to apply the changes.
