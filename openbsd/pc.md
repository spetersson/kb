# OpenBSD PC

## Caveats

### CTRL + A does not mark all text

OpenBSD gtk key-theme defaults to Emacs bindings which means that Ctrl + A will not mark all avalible text. However this can be changed to the default behavior.

Add the following in `~/.config/gtk-3.0/settings.ini`:

```
[Settings]
gtk-key-theme-name = "default"
```

Restart of window manager was not necessary for me. But might be for you.
