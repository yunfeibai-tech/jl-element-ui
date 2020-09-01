> A Vue.js 2.0 UI Toolkit for Web.
## Version
- v1.0.0 (fork element ui v2.13.2) 
 - v1.0.1 (fixed tab切换阴影问题 --涉及到tab组件) 


## Install
```shell
npm install jl-element-ui -S
```

## Quick Start
``` javascript
import Vue from 'vue'
import Element from 'jl-element-ui'
import 'jl-element-ui/lib/theme-chalk/index.css';

Vue.use(Element)

// or
import {
  Select,
  Button
  // ...
} from 'jl-element-ui'

Vue.component(Select.name, Select)
Vue.component(Button.name, Button)
```
For more information, please refer to [Quick Start](http://element.eleme.io/#/en-US/component/quickstart) in our documentation.

## Browser Support
Modern browsers and Internet Explorer 10+.


## LICENSE
[MIT](LICENSE)
