安卓企业微信下，会话中（含单聊和群聊，不含文件传输助手），
页面 A 跳转页面 B 时，页面 B 获取到的 `document.documentElement.clientWidth` 异常，
异常值 = 正常值 _ `window.devicePixelRatio`，如 `1080 = 384 _ 2.8125`
