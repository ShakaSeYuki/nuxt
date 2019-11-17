# Todo

Repository to create todo list (Vue / Nuxt / React / Next / Angular)

# DEMO

"hoge"の魅力が直感的に伝えわるデモ動画や図解を載せる

# Features

Check how much the configuration changes as you study each framework.

* Vue
* Nuxt
* React
* Next
* Angular

# Requirement

Library used separately for MAC and Windows.

* homebrew(MAC) 2.1.16
* nodebrew(MAC) 1.0.1
* nvm(Windows) 1.1.7

Move to each README

* [for-vue](https://github.com/ShakaSeYuki/todo/blob/master/for-vue/README.md)
* [for-nuxt](https://github.com/ShakaSeYuki/todo/blob/master/for-nuxt/README.md)
* [for-react](https://github.com/ShakaSeYuki/todo/blob/master/for-react/README.md)
* [for-next](https://github.com/ShakaSeYuki/todo/blob/master/for-next/README.md)
* [for-angular](https://github.com/ShakaSeYuki/todo/blob/master/for-abgular/README.md)

# Installation

Run if node.js is not installed.

for MAC

```bash
# Install hoembrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# Check homebrew version
brew -v

# Install nodebrew
brew install nodebrew

# Check nodebrew version
nodebrew -v

# Add to .bash_profile(/Users/[your-name])※1
vi .bash_profile

# Check node list
nodebrew ls-all

# Install node(stable/latest/any version)※2
nodebrew install-binary stable

# Set node version to use
nodebrew use v12.13.0

# Check node & npm version
node -v
npm -v
```

※1 add .bash_profile
```bash
# nodebrew
export PATH=$HOME/.nodebrew/current/bin:$PATH
```

※2 if nodebrew install-binary  
Warning: No such file or directory
and Warning: Failed to create the file
```bash
# Create src directory
mkdir -p ~/.nodebrew/src
```

for Windows  
download nvm-windows(nvm-setup.zip): [link](https://github.com/coreybutler/nvm-windows/releases)

```bash
# Check nvm version
nvm version

# Check node list
nvm list available

# Install node(any ver)
nvm install 12.13.0

# Set node version to use
nvm use 12.13.0

# Check node & npm version
node -v
npm -v
```
# Usage

DEMOの実行方法など、"hoge"の基本的な使い方を説明する

```bash
# clone repository
git clone https://github.com/ShakaseYuki/todo.git
```

# Note

注意点などがあれば書く

# Author
* [Yuki Nishino](https://github.com/ShakaSeYuki)
* [Twitter](https://twitter.com/ShakaSeYuki)

# License
"todo" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
