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

# Preview
<img width="948" height="1035" alt="image" src="https://github.com/user-attachments/assets/5c1c8110-8648-472d-a6c3-59845cbd1a04" />
