# Naruto

**English** · [Español](README.es.md)

A dark Omarchy theme inspired by Naruto: near-black charcoal, amber orange,
golden yellow and coral red, with ivory text and warm gray comments.

## Palette

`colors.toml` is the single source of colors. Omarchy generates the config for
every app from it (terminal, Hyprland, btop, Neovim, etc.), so the theme needs
no Lua or app-specific configs.

- The palette is warm (orange, gold, coral), but green and blue are genuinely
  muted hues (leaf green and steel blue) so diffs, errors and warnings stay easy
  to tell apart in the terminal.
- In Neovim (Aether v3): orange keywords, steel blue functions, parchment
  strings and coral errors.
- Icons: `icons.theme` uses Yaru with orange folders.

If your Neovim config forces transparency, turn it off to keep the theme's dark
backgrounds.

## Installation

```sh
omarchy theme install https://github.com/zamuxdev/omarchy-naruto-theme
```

Or copy this folder to `~/.config/omarchy/themes/naruto` and run:

```sh
omarchy theme set naruto
```

If you edit `colors.toml`, run the same command again to apply the changes.

## Backgrounds

The theme includes two backgrounds:

- `backgrounds/nostalgia-minimal.png`: a pencil-drawn swing on a charcoal
  background, with falling orange leaves. It is an AI-generated illustration made for
  this theme, with indirect references and no logos or frames from the anime.
- `backgrounds/omarchy.png`: the Omarchy logo in amber orange on charcoal, in
  the theme's colors.

You can add more backgrounds to `~/.config/omarchy/backgrounds/naruto/` and
cycle through them with:

```sh
omarchy theme bg next
```

Dark backgrounds with orange or gold tones work best.

## Note

Unofficial fan theme. Naruto and its characters belong to their respective
owners; this theme is not affiliated with or endorsed by them.
