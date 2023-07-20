# Solarized

A really simple [solarized color scheme][solarized] for Neovim, written to be as
simple as it gets and with additional two colors for a bit of added contrast:
_Base04_ (`#002028`) and _Base4_ (`#FFFFED`).

[solarized]: https://ethanschoonover.com/solarized/

## Why?

Why not? ;)

## Getting Started

### Requirements

- Neovim :P
- `vim.opt.termguicolors = true` in your `init.lua`.
- A terminal with [true color support][truecolor].

[truecolor]: https://github.com/termstandard/colors

### Installation

Install with your favorite package manager, e.g with [lazy.nvim][lazy]:

```lua
require('lazy').setup {
  'fschauen/solarized.nvim'
}
```

[lazy]: https://github.com/folke/lazy.nvim

### Setup

Just type:

```viml
:colorscheme solarized
```

or add this to your `init.lua`:

```lua
vim.cmd [[colorscheme solarized]]
```

### Options

None. This is supposed to be simple, remember?

## Supported Plugins

- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- [nvim-tree](https://github.com/kyazdani42/nvim-tree.lua)
- [indent-blankline](https://github.com/lukas-reineke/indent-blankline.nvim)
- [virt-column.nvim](https://github.com/lukas-reineke/virt-column.nvim)
- [vim-better-whitespace](https://github.com/ntpeters/vim-better-whitespace)
- [telescope](https://github.com/nvim-telescope/telescope.nvim)
- [vim-fugitive](https://github.com/tpope/vim-fugitive)

