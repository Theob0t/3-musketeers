# Cash 💸 

<img src="imgcash.jpg" >

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- :speech_balloon: [Description](#-description) 💬
- ❓ [How to use it](#-how-use-it) ❓
- 🔧 [Build With](#-build-with) 🔧
- 🔑 [Licence](#-licence) 🔑

## Description

This program is a currency converter implemented in NodeJS.


## How to use it

Clone this repository : https://github.com/Theob0t/3-musketeers/

Install dependencies
```sh
❯ cd /path/to/workspace/3-musketeers/cash
❯ npm i
```

Launch the program
```sh
❯ node bin/index.js
```

Replace "amount" and "currency" with your values (ex: 100 JPY).
```sh
❯ node bin/index.js amount currency
```

Change the defaults currencies by modifying constants.js and change the constant DEFAULT_TO_CURRENCIES

```javascript
const DEFAULT_TO_CURRENCIES = ['USD', 'EUR', 'GBP', 'JPY'];
```
Becomes
```javascript
const DEFAULT_TO_CURRENCIES = ['USD', 'EUR', 'CAD', 'BZD','MXN'];
```

## Build With 

* [Java Script](https://www.javascript.com/) - Java Script 
* [npm](https://www.npmjs.com/) - Node js 
* [JSDoc](http://usejsdoc.org/)- JSDoc format


## Licence

[Uncopyrighted](http://zenhabits.net/uncopyright/)
