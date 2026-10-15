# PeiTotem

本仓库保存以下 Minecraft 玩法/资源的源文件，当前实现与历史版本按目录分开。

- 不死佩腾重制版

## 使用

在 datapacks/current 或 resourcepacks/current 中找到含 pack.mcmeta 的目录；将该完整目录复制到世界 datapacks 或客户端 resourcepacks。版本兼容范围以各目录的 pack.mcmeta 与原文件名为准。不要同时启用同一玩法的多个版本。libraries、tools 和 tests 为开发辅助内容。

## 历史版本

versions 中保留各原始 ZIP 的源文件快照和原有目录结构，不以当前实现覆盖历史文件。原压缩包名称见 SOURCE_MAP.json。已有 Git 历史和所有分支由导入步骤另行保留；当前准备目录不含 .git。

## 开发与依赖

生成脚本与可编辑素材随源码保存；对应 Minecraft 游戏本体和外部依赖不随仓库分发。

## 作者与授权

原始作者署名与历史保持不变。自有实现和修改使用根目录 LICENSE 的 All Rights Reserved 声明。历史快照中的作者信息保持原样。

新导入提交身份：FeiXiaoStudio <201218585+FeiXiaoStudio@users.noreply.github.com>。
