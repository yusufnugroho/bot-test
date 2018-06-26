# bot-test

## How To start
1) Register Telegram Account
2) using web browser
3) choose web telegram
4) login to telegram account
5) on search bar, type 'botfather'
6) click BotFather account to start chat
7) type '/help' to check all command

## how to create bot from BotFather
1) (on input text with BotFather account) type '/newbot'
2) (BotFather will ask name for your bot) type 'citybot'(example)
3) (BotFather will ask username for your bot and this username must end/postfix string with 'bot') type test_citybot
4) (If there is no duplicate or problem when creating username for your bot, you will get for accessing HTTP API)
5) you can start to search your bot username(example : test_citybot) 

## Coding Part
1) Install NodeJS (Version >= 8.11.3, link: https://nodejs.org/en/ )
2) Install Text Editor
3) Make new folder
4) Init nodejs project
```
$ npm init
```
5) type all data for initial project information
6) install telegraf library from NPM and save into package.json(dependency 'this file holds various metadata relevant to the project. This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.'-docs, nodejitsu)
```
$ npm install --save node-telegram-bot-api
```
7) (you can see sample code from this repository) copy all/git clone, if git clone. install depedencies on your root folder
```
npm install
```
8) Copy your bot token to config.js file
9) Start app
```
$ node index.js
```

## Sample Bot in Action
1) ./src/assets/sample/1.jpg