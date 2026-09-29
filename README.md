# ColorDuo · ColorOS 17 流畅版

这是基于 [daxiaamu/ColorDuo](https://github.com/daxiaamu/ColorDuo) 0.5.1 的独立适配版，应用包名为 `io.github.colorduo.coloros17`。适配目标是 OPPO PME110、ColorOS 17.0.0.102、系统桌面 17.3.12；其他设备和版本尚未验证。

当前版本在「倾斜」翻页时提供随角度变化的动态模糊。为了避免上一版严重卡顿，它使用单层原生模糊，暂不提供近侧清晰、远侧渐糊的空间梯度。真机上的同类渲染原型测得 0.48% 显示帧超时、12.91 ms 的第 95 百分位帧耗时；本次最终安装包尚未完成真机安装回读，因此作为测试版发布。

安装时请在 LSPosed 中启用 **ColorDuo · ColorOS 17**，作用域仅选系统桌面 `com.android.launcher`；原版 ColorDuo 应保持关闭。首次安装或升级后重启系统桌面或手机，并在桌面将翻页效果设为「倾斜」。两版不能同时启用。若效果异常，先在 LSPosed 中关闭本模块，再重启桌面，无需清除桌面数据。

APK 在 Releases 页面下载。项目遵循上游 [MIT 许可证](LICENSE)，第三方说明见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
