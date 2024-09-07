# Dotfiles

BTW, I use Arch

Okay, okay that's not what this project is about.

More of really just a place for me to leave the configurations that I make to my system in the case that I completely bork it or decide to switch to a new operating system (Something that I do end up do pretty often).

Other than that, feel free to use this on your system as well.

The current design language is to look "as close to a TUI as possible" aka. a terminal user interface. It's also fairly barebones without much of anything eccentric to make it super custom. I just think it's easy to use and gets the job done.

# Current Setup

- Zsh
  - It's simply a better shell. Bash works but being able to get theming as well as plugins for autocompletion is a total game changer. Fish is also really good and will probably be a better choice for someone who does not want to do as much customization.
  - For the framework, I am using Oh-my-zsh which takes a lot of the guesswork out of setting up Zsh and it's plugins/themes.
- hyprland
  - I don't use it's eye candy features for the most part though it may change in the future. Mainly it's just that it's popular, runs using Wayland and is actively developed.
- ~~fuzzel~~
  - ~~A simple minimal runner that I use. I was originally going to go with rofi but I was having issues with it flickering.~~
- sway-launcher-desktop
  - I swapped over to this from fuzzel because it is a TUI and fits the aesthetic that I was going for. To be honest, it's not a massive difference.
- waybar
  - This is basically the default top bar that most people use. I just took the default configuration that it comes with and made it monotone as well as disabled most of the things that do not work on Hyprland or at least things that I have been bothered enough to figure out.
- neovim
  - I just threw on LazyVim for easy setting up of language support though it's not necessary.
