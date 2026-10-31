# shrd

Personal fork of [dwl](https://codeberg.org/dwl/dwl) — a compact, hackable
Wayland compositor based on [wlroots], in the spirit of [dwm].

## Build

Dependencies: libinput, wayland, wlroots 0.20 (libinput backend), xkbcommon,
wayland-protocols, pkg-config. For XWayland also libxcb, libxcb-wm; uncomment
the XWayland flags in `config.mk`.

```bash
make
sudo make install
```

## Configuration

Edit `config.h` and recompile.

## License

GPL-3.0 — see `LICENSE`. Based on dwl (GPL-3.0); parts derive from dwm, sway
and tinywl (MIT, see `LICENSE.dwm`, `LICENSE.sway`, `LICENSE.tinywl`).

[wlroots]: https://gitlab.freedesktop.org/wlroots/wlroots
[dwm]: https://dwm.suckless.org
