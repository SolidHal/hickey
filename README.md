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

black       ![#140a1d](https://via.placeholder.com/15/140a1d/000000?text=+) `#140a1d`<br />
red         ![#B52A5B](https://via.placeholder.com/15/B52A5B/000000?text=+) `#B52A5B`<br />
green       ![#FF4971](https://via.placeholder.com/15/FF4971/000000?text=+) `#FF4971`<br />
yellow      ![#8897F4](https://via.placeholder.com/15/8897F4/000000?text=+) `#8897F4`<br />
blue        ![#bd93f9](https://via.placeholder.com/15/bd93f9/000000?text=+) `#bd93f9`<br />
magenta     ![#E9729D](https://via.placeholder.com/15/E9729D/000000?text=+) `#E9729D`<br />
cyan        ![#F18FB0](https://via.placeholder.com/15/F18FB0/000000?text=+) `#F18FB0`<br />
white       ![#f1c4e0](https://via.placeholder.com/15/f1c4e0/000000?text=+) `#f1c4e0`<br />
black       ![#a8899c](https://via.placeholder.com/15/a8899c/000000?text=+) `#a8899c`<br />
red         ![#B52A5B](https://via.placeholder.com/15/B52A5B/000000?text=+) `#B52A5B`<br />
green       ![#FF4971](https://via.placeholder.com/15/FF4971/000000?text=+) `#FF4971`<br />
yellow      ![#8897F4](https://via.placeholder.com/15/8897F4/000000?text=+) `#8897F4`<br />
blue        ![#bd93f9](https://via.placeholder.com/15/bd93f9/000000?text=+) `#bd93f9`<br />
magenta     ![#E9729D](https://via.placeholder.com/15/E9729D/000000?text=+) `#E9729D`<br />
cyan        ![#F18FB0](https://via.placeholder.com/15/F18FB0/000000?text=+) `#F18FB0`<br />
white       ![#f1c4e0](https://via.placeholder.com/15/f1c4e0/000000?text=+) `#f1c4e0`<br />
background  ![#09090d](https://via.placeholder.com/15/09090d/000000?text=+) `#09090d`<br />
foreground  ![#e3c7fc](https://via.placeholder.com/15/e3c7fc/000000?text=+) `#e3c7fc`<br />
cursor      ![#f1c4e0](https://via.placeholder.com/15/f1c4e0/000000?text=+) `#f1c4e0`<br />



## Screenshots

TODO
