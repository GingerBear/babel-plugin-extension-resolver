# babel-plugin-extension-resolver

resolve
```
import SomeComponent from './SomeComponent'
```

to 

```
import SomeComponent from './SomeComponent.ios.js' // or
import SomeComponent from './SomeComponent.androd.js' // or
import SomeComponent from './SomeComponent.web.js' // or other extensions
```