# fis3-parser-es3ify
FIS3 transform to convert ES5 syntax to be ES3-compatible

基于[es3ify](https://github.com/spicyj/es3ify)

install:
```
npm install --save-dev fis3-parser-es3ify
```

usage：

```js
fis.match('/components/antd/lib/**.js', {
    parser: fis.plugin("es3ify")
})

```

类似工具：
- [fis3-parser-translate-es3ify](https://github.com/codering/fis3-parser-translate-es3ify)
- [es3ify-loader](https://github.com/sorrycc/es3ify-loader)
