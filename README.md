# dottie
A Bash script meant to put desired dotfiles in a single directory, optionally create a git repository for it, and create symbolic links for the dotfiles to still function. Helps the seamless transition from one system to the next, with all your configs transferred with only a single command.

## Getting Started

PLEASE NOTE: I am not responsible for any damage this script does to your system or the applications installed to your system. It is still in early development, use at your own risk.

So far this script only works with predefined entries and paths to configuration files in either ~/ or ~/.config directories. Support for automatic file detection/searching, argument-defined config generation, and auto-initialization of a git repository is under way.

### Prerequisites

+ Bash/Zsh or similar
+ Unix-like operating system

### Running

Navigate to installation directory, then run: 
```
./dottie
```
Optionally, you may add it to your 
```
/usr/local/bin/
```
in order to bypass constantly switching to the installation directory.

## License

This project is licensed under the GNU General Public License - see the [LICENSE](LICENSE) file for details
