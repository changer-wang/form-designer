**本项目是基于 [@form-create/element-ui](https://github.com/xaboy/form-create) 的扩展实现，主要增强组件间的动态联动功能（显示/隐藏），仅兼容 Vue 3**

**NodeJs:**

```shell
npm install @wang-form-create/designer@next
npm install @form-create/element-ui@next
npm install element-plus
```

```js
import FcDesigner from '@wang-form-create/designer'
import ELEMENT from 'element-plus';
import 'element-plus/dist/index.css';

app.use(ELEMENT);
app.use(FcDesigner)
app.use(FcDesigner.formCreate)
```

## 使用

```html
<fc-designer ref="designer"/>
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2021-present xaboy
