---
title: "API: watchers プロパティ"
description: watchers プロパティで監視設定を上書きできます。
---

# watchers プロパティ

- タイプ: `オブジェクト`
- デフォルト: `{}`

> nuxt.config.js 内の watchers プロパティで監視設定を上書きできます。

## chokidar

- タイプ: `オブジェクト`
- デフォルト: `{}`

chokidar オプションについてより深く理解するには [chokidar API](https://github.com/paulmillr/chokidar#api) を参照してください。

## webpack

- タイプ: `Object`
- デフォルト:

```js
watchers: {
  webpack: {
    aggregateTimeout: 300,
    poll: 1000
  }
}
```

webpack の監視オプションについてより深く理解するには [webpack のドキュメント](https://webpack.js.org/configuration/watch/#watchoptions) を参照してください。
