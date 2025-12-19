# How to install?
Put this inside your colorscheme.lua
```lua
return {
  {
    "jmp4zazel/sillyazazel",
    lazy = false,
    priority = 1000,
    config = function()
      vim.opt.termguicolors = true
      vim.cmd("colorscheme sillyazazel")
    end,
  },
}
```
