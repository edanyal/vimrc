## Installation

After you backup your `~/.vimrc` file and `~/.vim/` folder (this is not important if you haven't used Vim before), you can install this by running this bash line, press enter if you see any error messages:

```bash
echo "runtime vimrc" > ~/.vimrc && mkdir ~/.vim && cd ~/.vim && git clone https://github.com/edanyal/vimrc.git . && git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim && vim +PluginInstall
```

You're all set! Enjoy!

## Shortcuts

`<Leader>` is defined as the `\` key by default. `C-x` means Control + x and `M-x` means Meta-x. (*alt* or *option* in modern keyboards) `S-x` means Shift-x.

* `<Leader>y`: Copy to system clipboard
* `<Leader>d`: Cut to system clipboard
* `<Leader>p`: Paste below, from system clipboard
* `<Leader>P`: Paste above, from system clipboard
* `<F5><F5>`: Toggle paste mode. (Not important if you're using the shortcuts above.)
* `<F5>`: Reload Vim settings
* `<Leader>n`: New empty tab.
* `<Space>x`: Remove search highlight.
* `<Leader>]`: Open/Close NERDTree
* `<Leader>[` : Navigate between split views
* `<Tab>`: Buffer list (Normal Mode)
* `C-p`: Fuzzy finder
* ``<Leader>` ``: Swap the positions of the open splits
* `<Space>w`: Next sub-word in a camel cased word
* `<Space>b`: Previous sub-word in a camel cased word
* `<Space>e`: End of sub-word in a camel cased word
* `C-n`: Add the next occurrence of the selection to the multiple cursor selection

