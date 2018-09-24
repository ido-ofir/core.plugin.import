# core.plugin.import

handles 3rd party imports

```js
let core = new require('core.constructor')();
 
 core.plugin(
     require('core.plugin.import')
 );
 
 core.import('React', require('react'));
 
 core.imports.React;
```
