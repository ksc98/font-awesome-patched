# font-awesome-patched

A patched build of Font Awesome 7 Brands with the OpenAI (`U+E7CF`) and Claude (`U+E861`) glyphs scaled up so they read clearly at small sizes (e.g. status bars, terminal UI).

## File

- `fa-brands-patched.otf` — internal name `Font Awesome 7 Brands Tmux`. Drop-in for any place you'd use `Font Awesome 7 Brands`.

## Install

macOS:

```sh
cp fa-brands-patched.otf ~/Library/Fonts/
```

Linux:

```sh
mkdir -p ~/.local/share/fonts
cp fa-brands-patched.otf ~/.local/share/fonts/
fc-cache -f
```

## License

Glyphs are from [Font Awesome Free](https://fontawesome.com/) under the [SIL Open Font License 1.1](https://scripts.sil.org/OFL). This repo redistributes a modified build under the same license.
