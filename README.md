# **A Writer's NeoVim**
 
![Loading Screen](assets/LoadingScreen.png)
![Loading Screen](assets/FindFiles.png)
![Loading Screen](assets/FindWord.png)

OVIWrite is a [NeoVim](https://neovim.io/) powered Integrated Writing Environment (IWE) built using [LazyVim](https://lazyvim.github.io/) and [💤 lazy.nvim](https://github.com/folke/lazy.nvim). 

# INSTALLATION

## ⚡️ REQUIREMENTS

- Neovim >= **0.8.0** and its associated dependencies (needs to be built with **LuaJIT**)
- Git >= **2.19.0** (for partial clones support)
- a [Nerd Font](https://www.nerdfonts.com/) **_(optional but highly recommended)_**
- LaTeX compiler
- [Pandoc](https://pandoc.org/)

### Unix Systems (Linux and MacOS)

```bash
git clone https://github.com/MiragianCycle/OVIWrite.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

### Windows

**Command Prompt**
```cmd
git clone https://github.com/MiragianCycle/OVIWrite.git %userprofile%\AppData\Local\nvim\

```

**Powershell**
```pwsh
git clone https://github.com/MiragianCycle/OVIWrite.git $env:USERPROFILE\AppData\Local\nvim\
```

## 🔌 PLUGINS 

| Plugins               | Type                                                                                |
|-----------------------|-------------------------------------------------------------------------------------|
| LanguageTool.lua      | Spelling and Grammar                                                                |
| alpha.lua             | Splash Screen                                                                       |
| autopairs.lua         | Automatically close brackets and quotation marks                                    |
| catppuccin.lua        | Color Scheme                                                                        |
| comment.lua           | Commenting of text                                                                  |
| fountain.lua          | Screenwriting                                                                       |
| fzf-vim.lua           | Fast search for files and words                                                     |
| goyo.lua              | Distraction Free Writing                                                            |
| gruvbox.lua           | Color Scheme                                                                        |
| img-clip.lua          | Paste images into Markdown and LaTeX buffers                                        |
| lazygit.lua           | Version control for GitHub                                                          |
| limelight.lua         | Distraction free writing                                                            |
| markdown-preview.lua  | Preview Markdown files                                                              |
| mason-lspconfig.lua   | LSP                                                                                 |
| mason.lua             | LSP                                                                                 |
| nightfox.lua          | Color scheme                                                                        |
| noice.lua             | System notifications                                                                |
| nvim-tree.lua         | File explorer                                                                       |
| nvim-treesitter.lua   | Treesitter integration                                                              |
| nvim-web-devicons.lua | Pretty icons                                                                        |
| nvimorgmode.lua       | Org-mode                                                                            |
| obsidianNvim.lua      | Support for editing Obsidian files                                                  |
| pomo.lua              | Pomodoro timer                                                                      |
| telescope.lua         | Telescope, for fast search across buffers, directories, help documentation, etc.,                                                                      |
| translate.lua         | Translate to and from English, Tamil, Sinhala and French                                                                                                 |
| twilight.lua          | Yet another distraction free writing aid                                                                                                                                             |
| vim-grammarous.lua    | Grammar checker                                                                                                                                                                                                               |
| vim-latex-preview.lua | Preview LaTeX documents                                                                                                                                                                                                                                                                             |
| vim-pencil.lua        | line wrapping for prose                                                                                                                                                                                                                                                                                                                                             |
| vim-wiki.lua          | Personal knowledge management tool                                                                                                                                                                                                                                                                                                                                                                                              |
| vim-zettel.lua        | Zettelkasten function                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| vimorg.lua            | additional Org-Mode support within NeoVim                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| vimtex.lua            | LaTeX support                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| whichkey.lua          | Keyboard binding lookup                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| zen-mode.lua          | Distraction Free writing                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

## 📺 SCREENSHOTS

Note: The screenshots below show a variety of color schemes at play: Nightfox, DawnFox and NordFox. Also included in the config: Gruvbox and flavours of Catppuccin. I've included my favourite color schemes; users are, of course, free to add whatever color scheme that is available in the NeoVim ecosystem.  

### Long-form Writing

- Longform Writing; LaTeX

![Loading Screen](assets/LaTeX.png)

![Loading Screen](assets/Essay.png)


- Longform Writing; Org-Mode
 
 
![Loading Screen](assets/Org.png)
 
 
- Longform Writing; Markdown

![Loading Screen](assets/Markdown.png)




### Screenwriting 

- Screenwriting in Fountain format

![Loading Screen](assets/Fountain.png)

### Note-taking and Research

- Zettelkasten 

![Loading Screen](assets/Zettle.png)
