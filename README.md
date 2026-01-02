# Why did you make this?
I don’t like using too many colors for my personal setup. I found [vim-256noir](https://github.com/andreasvc/vim-256noir), and it ended up being the best color scheme for me. I just added some purple accents, and now it’s perfect.

# How to install?
Put this inside your `colorscheme.lua`:
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

