# how i like ubuntu setup

## keyboard shortcut mods:
- Launch terminal: super+return
- Toggle maximization state: super+m
- Launch web browser: super+w
- Home folder: super+e
- Close window: super+q

**custom keyboard shortcuts**:
- `spotify` super+m

## settings
- display: 100%
- show battery percentage
- automatic time zone

## key mappings
`dconf write "/org/gnome/desktop/input-sources/xkb-options" "['caps:swapescape']"` to swap escape w caps lock.
`dconf write "/org/gnome/desktop/input-sources/xkb-options" "['caps:escape']"` to ... map caps lock to esc without swapping them. (preferred)

then 
    "keyboard.dispatch": "keyCode" in vscode settings.json

