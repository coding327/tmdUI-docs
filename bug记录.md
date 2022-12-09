# 包的版本包括问题

- 最好按照我下面这几个版本：

```json
{
  ...
    "devDependencies": {
    "node-sass": "^5.0.0",
    "sass-loader": "^5.0.0",
    "vuepress": "^1.8.2"
  }
}
```

# 部署问题

- 关于`vuepress`的`base`配置：

```txt
// https://www.cake.com/a/b/xxx/f/index.html
// base应该配置为
base: '/a/b/xxx/f/'
```