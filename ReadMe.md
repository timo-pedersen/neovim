# Neovim setup


## Prerequisits (automate)
Note:Install rg / fd first. At least rg is found by nvim and automatically set up (don't know if significant).

This is the set vars in clean nvim (Note 'after' dirs):
```
grepformat=%f:%l:%c:%m
grepprg=rg --vimgrep -uu
runtimepath=~\AppData\Local\nvim,~\AppData\Local\nvim-data\site,C:\Program Files\Neovim\share/nvim/runtime,C:\Program Files\Neovim\share\nvim\runtime\pack\dist\opt\matchit,C:\Program Files\Neovim\lib/nvim,~\AppData\Local\nvim-data\site\after,~\AppData\Local\nvim\after   
```

- nvim (winget install Neovim.Neovim)
- rg (winget install BurntSushi.ripgrep.MSVC)
- fd (winget install sharkdp.fd)
- fzf (winget install fzf) See: https://www.youtube.com/watch?v=qgG5Jhi_Els
- fzf.lua (https://github.com/ibhagwan/fzf-lua)

## Windows setup ('open in' &c)

## Set up file structure
- In: ~/AppData/Local/nvim
- init.lua
- lua/

## Set up fanzy init.lua (in progress)

## Get plugins
- Lazy (https://github.com/folke/lazy.nvim)
- Telescope (https://github.com/nvim-telescope/telescope.nvim)
- LSP (for starters: https://neovim.io/doc/user/lsp.html)
- Treesitter (https://github.com/nvim-treesitter/nvim-treesitter)
- fzf for nvim(? Use fzf-lua, older fzf.vim written for vim compatibility. See Telescope!)
- charp (omnisharp slow, investigate, https://github.com/jmederosalvarado/roslyn.nvim dead? - seems omnisharp only option for now...)


