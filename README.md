# RuvPay Wallet 

RuvPay allows you to encrypt your secret key and store it as a file locally on your computer. You can use it on Windows, Linux and Mac.

## Key Features

- No registration. Secret key and login information stored locally.
- Offline transaction signing. Protect the secret key from exposure to the Internet.
- Send/receive/convert lumens, assets and tokens.
- Buy/sell lumens, assets and tokens.
- Merge account.
- Create your own tokens.
- View balances and history.
- Manage trust lines, account data, inflation destination.
- Federation protocol support.
- Contacts support.
- Deposit/withdraw CNY, BTC.
- Participate ICO projects.

## Build

You should have Node.js installed. If not, install it ([Node version manager](https://github.com/creationix/nvm) is recommended).

- Run `npm install` to prepare.
  RUN `rm -rf node_modules/sodium-native/tmp ` \\ if erorr with libsodium
- Run `npm start` to develop.
- Run `npm run dist` to build. You can use `npm run mac`, `npm run win` or `npm run linux` to build application according your system.


