# Lumo — 下载与更新

macOS 划词翻译，常驻菜单栏。选中文字按一下快捷键就出译文，没选中就在同一个浮窗里打字翻译。需要 macOS 26。

[English](README.md)

**[下载最新版](https://github.com/max1874/lumo-releases/releases/latest)**（.dmg，已签名并经 Apple 公证）

装好之后不用再来这里：Lumo 自己每天检查一次更新，也可以在菜单栏里点「检查更新…」。

## 这个仓库放什么

- `appcast.xml`：更新源，Lumo 读它判断有没有新版本。
- Releases：每个版本的磁盘映像和它的 SHA-256。

源码不在这里。

## 校验下载

```sh
shasum -a 256 -c Lumo-1.0.2.dmg.sha256
```

镜像和里面的 .app 各自经过公证并装订票据，所以断网也能直接打开，不会弹「无法验证开发者」。
