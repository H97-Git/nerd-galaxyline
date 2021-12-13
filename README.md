# Fork of [nerd-galaxyline](https://github.com/Avimitin/nerd-galaxyline)

**Unmodified :**

![IMG](./image/nerd-galaxyline.png)

nerd-galaxyline is a modern and great-looking status bar theme for
[galaxyline](https://github.com/glepnir/galaxyline.nvim). Forked from
[evilline](https://github.com/LoydAndrew/nvim/blob/main/evilline.lua)
and have numerous changes been made in the appearance.

## Features

- ❌ Removed : <s>Support `coc.nvim` diagnostic information report.</s>
- ❌ Removed : <s>FileFormat</s>
- ✅ Replaced : The name of the current LSP. (Is it possible to cycle through multiple LSP ?)
- Full nerdfont icons.
- Looks well with vim-deus themes.
- Support automatic truncation of status text
- **Added support for [onedark](https://github.com/joshdick/onedark.vim)** ( [First tint of #282C34](https://www.color-hex.com/color/282c34) )
- Short line support
- **Added support for [CHADTree](https://github.com/joshdick/onedark.vim)**

**New :**
<img align="right" width="45%" src="./image/nerd-galaxyline-onedark.png"/>

- Now support different color scheme and will change background color automatically.

  Currently supported theme:

<img align="right" width="65%" src="https://user-images.githubusercontent.com/30021675/134806451-ac360666-70da-431f-8746-a086facfeaaf.png"/>

```text
    * ever forest
    * deus
    * gruvbox
    * onedark
```

![image](./image/short-line.png)

## Requirement

Requires neovim 0.5.0+ and a patched
[nerd font](https://www.nerdfonts.com/).

## Install

Using [vim-plug]()

```
Plug 'glepnir/galaxyline.nvim'
Plug 'H97-Git/nerd-galaxyline'
```

## License

MIT LICENSE
