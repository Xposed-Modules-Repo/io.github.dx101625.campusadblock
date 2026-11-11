# 校园设备去广告 / Campus AdBlock

面向胖乖生活、智趣校园独立 App 的 MIT 开源 Xposed 模块。清理已匹配广告，减少摇一摇与推广外跳；设备码与配置本地保存。

- 一个开关控制自动流程：开启直达订单预览，关闭仅去广告。
- 可选设备识别、机号/档位与支付偏好预选、图片识码、设备收藏。
- 最终付款由用户手动确认。
- 应用包名：`io.github.dx101625.campusadblock`。

## 下载与源码
- [下载安装包及校验文件](https://github.com/Xposed-Modules-Repo/io.github.dx101625.campusadblock/releases/latest)
- [源码与问题反馈](https://github.com/dx101625/campus-adblock)
- [旧包名迁移指南](https://github.com/dx101625/campus-adblock/blob/main/docs/package-migration.md)

## 适配范围
胖乖生活 1.144.0、1.145.0（299）、1.146.0（300），智趣校园 6.5.29。自动选机与推进以胖乖吹风设备页验证为基准，不代表所有设备类型均支持。

v1.6.5 已在胖乖生活 1.146.0 真机验证自动直达原生订单预览，以及银联支付、抖音支付预选。测试停在订单预览，智趣校园本轮未复测。

旧版 `com.campus.adblock` 无法被新包名覆盖。先导出/导入配置，在框架关闭旧模块、启用新版并重选作用域，确认迁移正常前保留旧数据。

本仓库仅维护分发信息；源代码继续在个人仓库维护。
