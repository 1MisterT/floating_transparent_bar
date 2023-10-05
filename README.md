# GNOME Shell Extension - Transparent Top Bar

A GNOME Shell extension that brings back the transparent top bar when free-floating in GNOME Shell 3.32.

I this extension is based of the [extension](https://github.com/lamarios/gnome-shell-extension-transparent-top-bar) from lamarios. It keeps all the features and adds a floating state, when there is no window maximized.

## License

This program is distributed under the terms of the GNU General Public License, version 2 or later.

## Development

### Wayland

Start child shell instance with reloaded extensions
```
MUTTER_DEBUG_DUMMY_MODE_SPECS=1920x1080 dbus-run-session -- gnome-shell --nested --wayland
```

### Xorg

Reload shell by pressing ALT+F2 type r in the input then enter.

### Compile schemas
```
cd ~/.local/share/gnome-shell/extensions/transparent-top-bar@ftpix.com
glib-compile-schemas schemas/
```

