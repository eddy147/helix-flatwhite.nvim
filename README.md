# helix-flatwhite.nvim

A light Neovim colorscheme inspired by Helix's flatwhite style.

![helix-flatwhite](./Screenshot_2026-08-27_08-52-00.png)

## Installation

### lazy.nvim

```lua
{
  "eddy147/helix-flatwhite.nvim",
  priority = 1000,
  config = function()
    vim.cmd.colorscheme("helix-flatwhite")
  end,
}
```

### packer.nvim

```lua
use {
  "eddy147/helix-flatwhite.nvim",
  config = function()
    vim.cmd("colorscheme helix-flatwhite")
  end,
}
```

## Usage

```lua
vim.cmd.colorscheme("helix-flatwhite")
```

## Highlights Included

- Core editor UI groups (`Normal`, `CursorLine`, `StatusLine`, `Pmenu`, etc.)
- Tree-sitter and LSP semantic tokens
- Diagnostics and diff highlights
- Plugin groups for GitSigns, mini.indentscope, and Snacks.nvim

## License

[MIT](./LICENSE)
# helix-flatwhite
