# Lizzie 多人联棋插件（PairGo Plugin）

给 **LizzieYzy 2.5.3**（含智子围棋电脑版内置 Lizzie）增加「联棋 / 多人约战」功能：黑白各 1~3 座，人类 / AI / 空混编，支持本地联棋与局域网多人房间。

## ⬇ 下载最新版 3.0.25

**[lizzie-multiplayer-plugin-3.0.25.zip](https://github.com/kindlingycs-source/lizzie-multiplayer-plugin/releases/download/v3.0.25/lizzie-multiplayer-plugin-3.0.25.zip)**

下载后解压：

- 智子围棋电脑版：双击 **安装到智子围棋.bat**
- 普通 Lizzie jar 版：把整个文件夹放到 Lizzie 目录，双击 **启动联棋.bat**

## 3.0.25 更新

- 联棋人类限时与多人约战对齐：**0~180 的整数，0 = 不限时**（显示“不限时”，不计时、不判超时、不读秒）。
- 人类限时最后 10 秒语音读秒 **10、9、8…1**，与界面秒数同步。
- 修复连续开新局后右下小盘残留上一局棋子/变化图。
- 修复停局后顶部按钮卡在“结束对局”、点击无反应。
- 纯净对弈：棋盘、右下小盘、右侧变化树、候选表全部隐藏胜率信息；数据照常保存，终局后原样恢复，可直接复盘。
- 兼容 LizzieYzy 2.5.3（`lizzie-yzy2.5.3-shaded.jar`，MD5 `19e31482966b7bdb0eb042f45d4fb6e0`）。

## 入口

- 本地联棋：主界面 **Alt+L**
- 多人约战：**新对局 → 多人约战（真人联机）**

## 许可

基于开源项目 [lizzieyzy](https://github.com/yzyray/lizzieyzy)（GNU GPL v3）修改，只替换联棋相关类。修改后的源码随分发包 `源码/` 目录提供。
