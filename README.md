# Iosevka webfont

The [issue](https://github.com/google/fonts/issues/559) to add [Iosevka font](https://github.com/be5invis/Iosevka) doesn't seem to be processed. Therefore, I create my own Iosevka webfont hosting using Github Page (inspired by [Pvinis](https://github.com/pvinis/iosevka-webfont)).

## How to use

- Add `<link href="https://djsnipa1.github.io/iosevka--term-slab-webfont/latest/iosevka-term-slab.css" rel="stylesheet" />`. At this time, this is only the latest version hosted here (check the current latest version [here](./LATEST_RELEASE)).
- Use `fontFamily: 'Iosevka Term Slab Web'` or `font-family: 'Iosevka Term Slab Web'`.

## How to update

I use a [simple bash script](./get-fonts.sh) to get the latest release. Combining with Github action, it is looking for the new release everyday and update automatically.
