# GitHub 自动编译 APK

把 `android_mobile_app` 文件夹里的内容上传到你 GitHub 仓库的根目录（包含 `.github`、`app`、`build.gradle`、`settings.gradle`）。

上传完成后：
1. 打开仓库顶部的 **Actions**。
2. 点击 **Build Android APK**。
3. 点击右侧 **Run workflow**，再点击绿色按钮确认运行。
4. 等待出现绿色对勾。
5. 点进这次运行，在页面底部的 **Artifacts** 里下载 `word-review-apk`。
6. 解压下载的 artifact，里面就是 `app-debug.apk`，手机直接安装即可。

APK 固定打开：
https://wangc566.github.io/word-review-mobile/

注意：这是 debug APK，适合个人使用和测试。它不需要 Android Studio，也不需要在本机安装 Android SDK。
