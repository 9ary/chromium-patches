# Streetwalrus's Chromium patches

Nothing too fancy here, feel free to use them for your own builds. Most of these
target the Android version as I use Firefox on my computer.


## Included patches

- `ddg.patch`: adds DuckDuckGo to the default search engines, useful
for Android builds since these do not allow adding custom search engines
from the preferences.
- `context-menu.patch`: extends the Android context menu to show title text,
src URL and href URL on everything based on what is set. You can finally browse
[xkcd.com](https://xkcd.com/) and be able to see the hovertext. Also lets you
see what you would copy using the buttons.


## TODO

- Direct sharing of media from the context menu
- Option to open tabs in the background like Firefox Nightly does
- Firefox Sync integration
- Ad blocking via uBlock Origin (probably figure out how to get addons to work
on Android
- Remove some animations that slow down browsing like the "Open in new tab"
animation
- More ?
