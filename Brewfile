# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils
# Install Bash 4
install bash

# Install cask
tap phinze/homebrew-cask
install brew-cask

# Install wget with IRI support
install wget --enable-iri

# Install RingoJS and Narwhal
# Note that the order in which these are installed is important; see http://git.io/brew-narwhal-ringo.
#install ringojs
#install narwhal

# Install more recent versions of some OS X tools
install vim --override-system-vi
tap homebrew/dupes
install homebrew/dupes/grep
tap josegonzalez/homebrew-php
#install php53
#install php54
#install php55
install node
install go
install mongodb
install redis

# This formula didn’t work well last time I tried it:
#install homebrew/dupes/screen

# to manage your dotfiles
tap thoughtbot/formulae
install rcm

# Install other useful binaries
install safe-rm
install ack
#install exiv2
install git
install imagemagick
#install lynx
install ruby
install node
install pigz
install rename
install rhino
install tree
install webkit2png
#install zopfli
install p7zip
install ctags
install watch
# to change Ruby versions
install rbenv

tap homebrew/versions
install lua52

# Remove outdated versions from the cellar
cleanup
