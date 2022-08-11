# workspace

Project Title
A brief description of what this project does and who it's for

Installation
brew
https://docs.brew.sh/Installation
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" ... installing... ==> Next steps:

Run these two commands in your terminal to add Homebrew to your PATH: echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/lena/.zprofile eval "$(/opt/homebrew/bin/brew shellenv)"
check
brew -v

git
https://git-scm.com/download/mac
brew install git

check
git --version

Git ssh-keygen

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
ssh-keygen -t ed25519 -C "e.s.gontareva@gmail.com" Copy ssh key, go to https://github.com/settings/keys, and add ssh key

pbcopy < ~/.ssh/id_ed25519.pub

OR
cat ~/.ssh/id_ed25519.pub

oh-my-zsh
https://ohmyz.sh/#install
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

nvm
https://github.com/nvm-sh/nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

check
nvm -v

nodejs
https://github.com/nvm-sh/nvm
nvm install --lts

check
node -v
