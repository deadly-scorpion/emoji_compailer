# Emoji compiler
<a href="https://buymeacoff.ee/rBuzC4v" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

Node js compailer what auto convert code with emoji to code with emoji hex

# Features!
 - Replace emojis to emoji hex in all files.
 
# To Do
 - [ ] Ignore emoji in string.
 - [ ] Simple command compiler like scss compiler.

### Installation

Compiler requires [Node.js](https://nodejs.org/)


```sh
$ npm install
$ npm start
```

Edit code files in the /private dir
And auto compile code to /public dir


### Preview

./private/index.js
```js
var 
	🤪 = 'Hello',
	🚀 = 'world';

console.log(🤪 + 🚀)
```
./public/index.js
```js
var 
	e_1f92a = 'Hello',
	e_1f680 = 'world';

console.log(e_1f92a + e_1f680)
```
