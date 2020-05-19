# dotfiles
Uses the following :

------
<img src="https://raw.githubusercontent.com/neovim/neovim.github.io/master/logos/neovim-logo.png" width=160><img src="https://upload.wikimedia.org/wikipedia/commons/f/f6/OpenWeather-Logo.jpg" width=160><img src="https://raw.githubusercontent.com/capktkirk/dotfiles/master/polybar_logo.png" width=160><img src="https://raw.githubusercontent.com/capktkirk/dotfiles/master/plug.png" width=160>

-------

My build /dotfiles.

Steps to take to use these dotfiles.

The commands to install and use these dot files are different depending on your flavor of Linux. I am linking to their sources for ease of install.

* Install `i3-gaps`: [Here](https://github.com/Airblader/i3)
* Install `polybar`: [Here](https://github.com/polybar/polybar)
* Install `Neovim` : [Here](https://github.com/neovim/neovim/wiki/Installing-Neovim)
* Install `Plug`   : [Here](https://github.com/junegunn/vim-plug)


alacritty is the terminal I'm currently using, it hasn't had much customization.

Changes you will need to make :

* In Polybar there is a weather script in the scripts directory. You will need to sign up for an API key from OpenWeather and put it there.
* monitors.xml should be put in the config file if you have multiple monitors. Set them up to your specifications or use arandr/xrandr to export your own profile.
* The i3-gaps config file has a lot of specialized scripts for screenshots/volume increases/weather etc. These will need to be changed based on the software for sound/screenshots/whatever.

These dot files were collected from multiple sources, sources linked in files where applicable.
