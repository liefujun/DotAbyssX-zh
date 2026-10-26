# DotAbyss X (ドットアビスX) 简体中文汉化版 v1.14.6

基于官方 v1.14.6，集成社区简体中文翻译（LemonLoader + AbyssMod）。

## 包含文件

| 文件 | 说明 |
|------|------|
| `DotAbyss_1.14.6_zh-Hans.apk` | 汉化安装包（包名 `.mod`，可与原版共存） |
| `UnityCache.zip.part01` ~ `part04` | Unity 资源缓存（合并后解压使用） |

## 安装说明

1. 下载 `DotAbyss_1.14.6_zh-Hans.apk` 并安装
2. 首次启动会黑屏 1~3 分钟（LemonLoader 部署翻译数据，约 33 MB），属正常现象

## UnityCache 使用方法

把 4 个 part 文件合并成 `UnityCache.zip` 后解压，将 `UnityCache` 文件夹放到游戏数据目录：
`/sdcard/Android/data/jp.co.fanzagames_dotabyss_x_a.mod/files/UnityCache/`

**Windows 合并：**
```cmd
copy /b UnityCache.zip.part01 + UnityCache.zip.part02 + UnityCache.zip.part03 + UnityCache.zip.part04 UnityCache.zip
```

**Android / Linux 合并：**
```sh
cat UnityCache.zip.part01 UnityCache.zip.part02 UnityCache.zip.part03 UnityCache.zip.part04 > UnityCache.zip
```

## 注意事项

- 安装包为自签名（非官方签名），部分手机管家可能误报病毒，需添加信任
- 服务器维护期间可能出现错误码 11110，非安装包问题
- 包名 `jp.co.fanzagames_dotabyss_x_a.mod`，与官方版不冲突
