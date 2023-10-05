# GNOME Shell Extension - Transparent Top Bar

A GNOME Shell extension that brings back the transparent top bar when free-floating in GNOME Shell 3.32.

I this extension is based of the [extension](https://github.com/lamarios/gnome-shell-extension-transparent-top-bar) from lamarios. It keeps all the features and adds a floating state, when there is no window maximized.

## Preview

![grafik](https://github.com/1MisterT/floating_transparent_bar/assets/64922722/b270c52c-d522-4175-b2a2-0dffc42b63d8)
Floating top bar, when there is no maximized window.

![grafik](https://github.com/1MisterT/floating_transparent_bar/assets/64922722/485d3148-ce12-4324-9df0-7de70a6c5416)
Attached top bar.



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

