# Tuttiq's Dotfiles

Completely stolen from [etdev's dotfiles](https://github.com/etdev/dotfiles), with minor changes by me.

### Install

Clone the repo into your home folder:
```
cd ~
git clone https://github.com/tuttiq/dotfiles.git
```

Comment out stuff you don't want:

* [mac settings](https://github.com/tuttiq/dotfiles/blob/master/install_mac.sh#L192-L778)
* [brew packages](https://github.com/tuttiq/dotfiles/blob/master/lib_node/brew_packages.js)
* [brew casks](https://github.com/tuttiq/dotfiles/blob/master/lib_node/brew_casks.js)
* [npm packages](https://github.com/tuttiq/dotfiles/blob/master/lib_node/npm_packages.js)

Run the install script:
```
cd ~/dotfiles
./install.sh
```

Follow the instructions. That's it!

### Make your own customizations

Put your customizations in dotfiles appended with `.local`:

* `~/.aliases.local`
* `~/.vimrc.local`
* `~/.zshrc.local`
* etc.

To extend your `git` hooks, create executable scripts in
`~/.git_template.local/hooks/*` files.

### Thanks

- These dotfiles are completely stolen from [Etdev's Dotfiles](https://github.com/etdev/dotfiles).
  - That was originally forked from [Thoughtbot Dotfiles](https://github.com/thoughtbot/dotfiles).
  - The install script is from [Adam Eivy's Dotfiles](https://github.com/atomantic/dotfiles).
