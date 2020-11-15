# we-style

Common Style for wechart miniapp

## How to build

```shell
npm install -g less

lessc style.less dist/style.wxss
lessc style.less dist/style.css
```

## How to use

import style.wxss in your wxss file, app.wxss e.g.

```javascript
@import 'dist/style.wxss'
```
