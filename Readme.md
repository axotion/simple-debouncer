#Simple debouncer

It's so simple. I promise.

##How to install

```
npm i simple-debouncer
```

## How it works

For my needs, it will wait for last input change and execute (eg. requests, dispatching actions) so I can avoid multiple requests

```
<input type="text" onkeypress="debounce(() => { console.log('Yay') }, 3000)">
```


##How to use


```javascript
import { debounce }  from 'simple-debouncer'

//On input event change? Or even on computed? Your choice!

debounce( () => { console.log("Hello!")}, 3000)

```

Where 3000 is timeout waiting for input changes


And... that's it! Just simple debouncer for your needs

