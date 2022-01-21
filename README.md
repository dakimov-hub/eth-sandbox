# eth-sandbox
Development environment and sandbox

# Prepare environment

## Some tools and packages

```
sudo apt-get install git-all
```

## Chrome

```bash
cd ~
mkdir distr
cd distr
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
````

## Metamask. react dev tools
[Metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)

## solc

[Solc installation](https://docs.soliditylang.org/en/v0.8.11/index.html)

```bash
sudo add-apt-repository ppa:ethereum/ethereum
sudo apt-get update
sudo apt-get install solc
```

## Nodejs
[Nodejs](https://nodejs.org/en/)

```bash
bash ~/.bashrc
sudo apt install curl
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

nvm install 16
nvm use 16
npm install web3
```
Switch to 12 version

```bash
nvm install 12
nvm use 12
nvm alias default 12
npm install npm --global
```

## Ganache
[Ganache](https://github.com/trufflesuite/ganache )

```bash
sudo apt-get install build-essential
npm install ganache --global
npm install web3  http-server
npm run dev
```

## Trufflesuite
[]()

```bash
```

## Visual Studio Code
[Visual Studio Code](https://code.visualstudio.com/docs/setup/linux)

```bash
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
sudo install -o root -g root -m 644 packages.microsoft.gpg /etc/apt/trusted.gpg.d/
sudo sh -c 'echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/trusted.gpg.d/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'
rm -f packages.microsoft.gpg

sudo apt install apt-transport-https
sudo apt update
sudo apt install code # or code-insiders
```

## hardhat
[hardhat](https://hardhat.org/tutorial/setting-up-the-environment.html)

```bash
mkdir hardhat
cd hardhat
npm init --yes
npm install --save-dev hardha
npm install --save-dev hardhat
```

## Remix Desktop
[Remix Desktop](https://github.com/ethereum/remix-desktop/releases)

```bash
wget https://github.com/ethereum/remix-desktop/releases/download/v1.3.3/Remix-IDE-1.3.3.AppImage
chmod a+x Remix-IDE-1.3.3.AppImage 
```

## Atom 
[Atom](https://github.com/atom/atom/releases/tag/v1.58.0)

```bash

```

## template
[]()

```bash
```
