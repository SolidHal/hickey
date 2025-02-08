# hickey

like a bruise

* [Installation](#Installation)
  * [Vim/Neovim](#Vim--Neovim)
  * [Terminal](#Terminal)
    * [Shell](#Shell)
    * [ST](#ST)
* [Screenshots](#Screenshots)

## Installation

#### spacevim
```
[options]
    # set spacevim theme. by default colorscheme layer is not loaded,
    # if you want to use more colorscheme, please load the colorscheme
    # layer
    colorscheme = "hickey"
    colorscheme_bg = "dark"

[[custom_plugins]]
repo = "https://github.com/SolidHal/hickey"
merged = 0
```

####  vim-plug:
```vim
Plug 'SolidHal/hickey'
```

#### Packer:
```lua
use { 'SolidHal/hickey' }
```

#### Manual
```bash
mkdir ~/.config/nvim/colors/
ln ./colors/hickey.vim ~/.config/nvim/colors/
```

Finally in your `.vimrc` or `init.vim` set the colorscheme:

```vim
colorscheme hickey
```

### Alacritty
see alacritty.toml

### Terminal

Here is the color palette:

```
black = "#140a1d"
red = "#FF4971"
green = "#8897F4"
yellow = "#B52A5B"
blue = "#bd93f9"
magenta = "#E9729D"
cyan = "#F18FB0"
white = "#f1c4e0"
background = "#574464"
foreground = "#e3c7fc"
text = "#09090d"
cursor = "#f1c4e0"
```


## Screenshots

TODO
