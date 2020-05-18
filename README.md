# dotfiles
Uses the following :

![Neovim](https://raw.githubusercontent.com/neovim/neovim.github.io/master/logos/neovim-logo.png =160x)
![OpenWeather](https://upload.wikimedia.org/wikipedia/commons/f/f6/OpenWeather-Logo.jpg =160x)
![Polybar](polybar_logo.png =160x)
![neovim Plug](plug.png =160x)

-----

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
