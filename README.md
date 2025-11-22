# Meowllow for Neovim

## Installation

### Lazy.nvim
```lua
{
  "meowllow/nvim",
  name = "meowllow",
  priority = 1000,
  config = function()
    vim.cmd("colorscheme meowllow-purr") -- Set your default theme here.
  end,
}
```

### Mini.deps
```lua
add({ source = "meowllow/nvim", name = "meowllow" })
```

### Packer.nvim
```lua
use { "meowllow/nvim", as = "meowllow"}
```

### Vim-Plug
```lua
Plug 'meowllow/nvim', {'as': 'meowllow' }
```

---

Made with ❤️ by [hxpe](https://github.com/hxpe-dev)  
If you enjoy **Meowllow**, consider starring the [GitHub repository](https://github.com/Meowllow/meowllow)!
