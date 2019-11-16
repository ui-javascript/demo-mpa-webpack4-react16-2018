# README

webpack4-react多页面模板

打包构建的配置文件被我写残了， 仅供学习!! 

# 使用

- 首字母小写的js作为entry
- 样式一律用`scss`
- config/index.js里选择入口
- react-dom挂载结点

```jsx
ReactDOM.render(<App />, document.getElementById("root"))
```

# TODO

- 处理css格式
- 各个工程/页面使用各自的static路径

# FIXME

- @fix Browserslist: caniuse-lite is outdated. Please run next command `yarn upgrade caniuse-lite browserslist`
