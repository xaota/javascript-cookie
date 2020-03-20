# javascript-cookie

### Установка
```shell
$ npm install javascript-cookie
```

Надо настроить в вашем сервере резолв с `/javascript-cookie` в `node_modules/javascript-cookie`

```html
<script type="importmap">
{
  "imports": {
    "javascript-cookie": "/javascript-cookie/browser.js"
  }
}
</script>
```

### Использование
```javascript
import Cookie from 'javascript-cookie';

Cookie.set(name, value, options); //
Cookie.get(name);                 // value
Cookie.remove(name);              //
```

### ROADMAP
server api
