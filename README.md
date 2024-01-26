# St (Simple Terminal)

St is a simple terminal emulator for X which sucks less.

## Dependencies

St depends on the Xlib header files. Install it according to your distro.

## Install

```shell
git clone https://github.com/dagregi/st.git
cd st
sudo make install
```

## Configuration

Defaults configuration are stored in `config.def.h`. Edit it according to your needs. 

## Patches:

- [anysize](https://st.suckless.org/patches/anysize/)
- [boxdraw](https://st.suckless.org/patches/boxdraw/)
- [bold-is-not-bright](https://st.suckless.org/patches/bold-is-not-bright/)
- [clipboard](https://st.suckless.org/patches/clipboard/)
- [scrollback](https://st.suckless.org/patches/scrollback/)
- sixel
- [wide-glyphs](https://www.reddit.com/r/suckless/comments/jt90ai/update_support_for_proper_glyph_rendering_in_st/)
- [xresources](https://st.suckless.org/patches/xresources/)
- [xresources live reload](https://st.suckless.org/patches/xresources-with-reload-signal/)

## Xresources live-reload

```shell
xrdb -merge path/to/xresources
pkill -USR1 st
```

## Themes/Fonts used

- Font: [JetbrainsMono Nerd Font](https://www.nerdfonts.com/font-downloads)
- Theme: [RoséPine](https://rosepinetheme.com)

# Credits

- [sixel support](https://github.com/bakkeby/st-flexipatch)
