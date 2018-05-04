### 目录结构
- `actions`用于存放每个功能节点下合成`actions`。当某些操作，需要合成多个不同`store`下的`action`时，在这里合并成一个方法
- `stores`我们将原来组件里的`props`和`state`拿出来作为一个类，进行监听管理。
- `assets`存放在资源（图片）
- `components`存放UI组件和木偶组件
- `containers`容器组件，进行UI组件整合，负责处理业务逻辑与数据绑定
- `routes`放置路由文件
- `index.js`入口文件
