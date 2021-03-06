# i3lock-arc

**Arc Dark theme for [i3lock-color](https://github.com/Raymo111/i3lock-color)**.

![](https://raw.githubusercontent.com/DAMO238/i3lock-arc/master/demo-arc-dark.gif)

## Dependencies

The only dependency is [i3lock-color](https://github.com/Raymo111/i3lock-color), a simple screen locker with color functionality.
**Do not** try to use this script with [i3lock](https://i3wm.org/i3lock/).

## Installation instructions

Clone this repo and add the following to your i3 configuration file: (usually located at `$HOME/.config/i3/config`)

```
bindsym <KEYBOARD_SHORTCUT> exec <PATH_TO_I3LOCK_SOLARIZED>/bin/i3lock-arc-<STYLE>.sh
```

Replace

1. `<KEYBOARD_SHORTCUT>` with your preferred key combination (e.g., `Mod4+l`),
2. `<PATH_TO_CLONED_REPO>` with the path to the repo, and
3. `<STYLE>` with one of `light` or `dark`.

## Fork

This is a fork of the [i3lock-solarized](https://github.com/parsiad/i3lock-solarized) by parsiad.
