# vintage-sublime-surround

Vintage-sublime-surround is a [SublimeText 2](http://www.sublimetext.com/) plugin which adds [Vintage](http://www.sublimetext.com/docs/2/vintage.html) key mappings to [sublime-surround](https://github.com/jcartledge/sublime-surround) for a fuller [vim-surround](https://github.com/tpope/vim-surround)-like experience.

## Mappings

The added mappings are:

### `cs` in normal mode

Change surround around the current insertion point(s).

### `ds` in normal mode

Delete surround around the current insertion point(s).

### `ys<motion>` in normal mode

Wrap the selection defined by `<motion>` with something - e.g. `ys3iw` wraps 3 words beginning with the word containing the insertion point(s).

### `s` in visual mode

Wrap the visual selection with something. Note that this overrides the Vintage-defined (and Vim) behaviour of `s` in visual mode which deletes the visual selection and enters insert mode - you can still use `c` to do this.

## Installation

### Using Git

Go to your Sublime Text 2 `Packages` directory and clone the repository using the command below:

`$ git clone https://github.com/jcartledge/vintage-sublime-surround.git`

### Download Manually

Download the files using the .zip download option.  
Unzip the files.  
Copy the folder to your Sublime Text 2 Packages directory.

### Package Control

This plugin is not yet available in the Package Control repository.

If you really can't wait, [here are instructions](http://wbond.net/sublime_packages/package_control/usage) (under **Add Repository**) for using Package Control to install plugins which are not in the official repository.

