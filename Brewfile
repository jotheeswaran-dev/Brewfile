# ~/Brewfile

# This file is used along with the `brew bundle` command to ensure that required packages and apps are installed.
# Also can be used to ensure that any package/apps that were installed as experimentation are uninstalled from the system.
# If you are starting such a file on a machine where you have already installed some apps using brew, then use `brew bundle dump` to create this file and avoid starting from scratch

# List all casks that are outdated (and which have version marked as 'latest')
# alias bcg='brew outdated --greedy'

# Upgrades all casks that are outdated (and which have version marked as 'latest')
# alias bcug='brew upgrade --greedy'

# Upgrades and cleans up all regular outdated casks and libs (non-greedy)
# alias bupc='brew bundle check || brew bundle --all --cleanup; brew bundle cleanup --force; brew cleanup --prune=all; brew upgrade'

# Note: Not yet found casks for the following:
# https://www.cockos.com/licecap/

# set arguments for all 'brew cask install' commands
cask_args appdir: '/Applications'

tap "adoptopenjdk/openjdk"
tap "azure/functions"
tap "homebrew/bundle"
tap "homebrew/cask"
tap "homebrew/core"
tap "homebrew/services"
brew "autoconf"
brew "awscli"
brew "guile"
brew "libidn2"
brew "p11-kit"
brew "unbound"
brew "gnutls"
brew "emacs"
brew "cask"
brew "glib"
brew "libssh"
brew "qemu"
brew "lima"
brew "colima"
brew "openldap"
brew "curl"
brew "docker"
brew "docker-compose"
brew "freetds"
brew "gimme-aws-creds"
brew "git"
brew "libfido2"
brew "libpq"
brew "mysql", restart_service: true
brew "nghttp2"
brew "openjdk@11"
brew "php"
brew "php@7.4", restart_service: true
brew "postgresql@14"
brew "python@3.9", link: false
brew "saml2aws"
brew "talisman"
brew "terraform"
brew "vim"
brew "zsh"
brew "azure/functions/azure-functions-core-tools@3"

cask "iterm2"
cask "adoptopenjdk8"
cask "alt-tab"
cask "balance-lock"
cask "google-cloud-sdk"
cask "insomnia"
cask "laravel-kit"
cask "ngrok"
cask "rancher"
cask "rectangle"
cask "tableplus"
cask "warp"
cask "xampp-vm"
cask "zoom"
cask "google-chrome"
cask "brave-browser"
cask "spotify"
cask "1password"
cask "1password-cli"
cask "microsoft-remote-desktop"
cask "microsoft-office"
cask "slack"
cask "postman"
cask "raycast"

# cask 'microsoft-teams'

# Heroku - in case we want to deploy using the heroku-cli
# tap 'heroku/brew'
# brew 'heroku'

