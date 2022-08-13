# workspace

<details>
  <summary>brew</summary>
  
  #### Installation
  https://docs.brew.sh/Installation
  
  ```sh
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
  ```

  ```sh
    ...
    installing...
    ==> Next steps:
    - Run these two commands in your terminal to add Homebrew to your PATH:
        echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/lena/.zprofile
        eval "$(/opt/homebrew/bin/brew shellenv)"
  ```
  
  ```sh
  echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/lena/.zprofile
  eval "$(/opt/homebrew/bin/brew shellenv)"
  ```

  #### Check

  ```sh
  brew -v
  ```

</details>

<details>
 <summary>git</summary>

#### Installation
https://git-scm.com/download/mac
  
```sh  
brew install git
```
  
#### Check
  
 ```sh 
git --version
```

### Git ssh-keygen
```sh
# https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
ssh-keygen -t ed25519 -C "e.s.gontareva@gmail.com"
```
Copy ssh key, go to https://github.com/settings/keys, and add ssh key
```sh
pbcopy < ~/.ssh/id_ed25519.pub
# OR
cat ~/.ssh/id_ed25519.pub
```
</details>
  
<details>
<summary>oh-my-zsh</summary>
#### Installation
https://ohmyz.sh/#install

```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
</details>
  
<details>
  <summary>nvm</summary>
  #### Installation
  https://github.com/nvm-sh/nvm
  ```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
 ``` 
#### Check
```sh
nvm -v
```
</details>

  <details>
<summary>node js</summary>
```sh
# https://github.com/nvm-sh/nvm
nvm install --lts
    
#### Check
```sh
node -v
```
</details>
