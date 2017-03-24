# hello-react
https://www.codementor.io/tamizhvendan/beginner-guide-setup-reactjs-environment-npm-babel-6-webpack-du107r9zr

https://github.com/facebookincubator/create-react-app

## Install nodejs and yarn:

```bash
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash - &> /dev/null
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt-get update
sudo apt-get -y --force-yes install nodejs yarn
```

## Install Dependencies:

```bash
yarn install
```

## Build for dev:

```bash
yarn run dev
```