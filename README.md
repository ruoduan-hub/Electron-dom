## Electron-react-App



###  star

`yarn start` 起web服务

`yarn electron-start` 起desktop 服务





### build

`yarn run dist`

main.js  如下 切换

```js
//   加载应用----react 打包
    mainWindow.loadURL(url.format({
        pathname: path.join(__dirname, './build/index.html'),
        protocol: 'file:',
        slashes: true
    }))

  // 加载应用----适用于 react 项目
  mainWindow.loadURL('http://localhost:3000/');
```



 TODO build 待解决

