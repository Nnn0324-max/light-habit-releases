# 轻习惯 发行物

这个仓库**只放发行物**，源代码不在这里。

- latest.json — App 检查更新时读取的清单；
- Releases — 每个版本的签名 APK。

App 内检查更新逻辑：读取 `latest.json`，比较 `build` 与 `version`，
有更新时在「我的 → 版本」显示，并在「关于轻习惯」提供下载入口。

字段说明见 latest.json。