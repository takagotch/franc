### franc
---
https://github.com/wooorm/franc

```
npm install franc

npm install franc-cli -global
franc ""
echo ""
franc --blacklist por,glg ""
echo "" | franc --whitelist nob,dan
```

```js
var franc = require('franc')
franc('the')
franc('the', {minLength: 3})

console.log(franc.all('xxx'))

console.log(franc.all('', {whitelist: ['por', 'spa']}))

console.log(franc.all('', {blacklist: ['src', 'glg']}))
```

```
```


