# Yup
Yet another Unnamed Project for Beth 2019

### Dependecies

Install `npm` and `node.js`:
```
apt install curl
curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -
apt install nodejs
echo "node `node -v`; npm `npm -v`" # check at least 10.x and 6.x
```

Install project dependecies:
```
npm install
```

To add a dependecy run:
```
npm install truffle --save
```

### Deploy smart contract

Need to install `truffle` and `ganache`.

To deploy open a terminal and run:
```
ganache
```

In another terminal run:
```
truffle compile
truffle deploy --reset
```
