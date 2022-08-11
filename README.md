# workspace

1. Install brew
# https://docs.brew.sh/Installation
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
...
installing...
==> Next steps:
- Run these two commands in your terminal to add Homebrew to your PATH:
    echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/lena/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
    
# check
brew -v

2. Install git
# https://git-scm.com/download/mac
brew install git
# check
git --version
Git ssh-keygen
# https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
ssh-keygen -t ed25519 -C "e.s.gontareva@gmail.com"
Copy ssh key, go to https://github.com/settings/keys, and add ssh key

pbcopy < ~/.ssh/id_ed25519.pub
# OR
cat ~/.ssh/id_ed25519.pub
