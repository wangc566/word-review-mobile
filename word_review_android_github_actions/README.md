# Android 手机版

这是一个 Android WebView 外壳，打开后固定访问：
`https://wangc566.github.io/word-review-mobile/`

固定入口页面会自动找到当前电脑的 Cloudflare Tunnel，所以 APK 不需要写死 `trycloudflare.com` 地址。

## 编译

使用 Android Studio 打开本目录。

要求：Android SDK 35。

然后 Build -> Generate App Bundles or APKs -> Generate APKs。
