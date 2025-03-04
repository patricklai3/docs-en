---
aside: true
titleTemplate: :title | 空荧酒馆
prev:
  text: '【隐藏】标记/【显示】标记'
  link: '../hide-show-done/hidedoneshowdone'
next:
  text: '【窗口全屏/无边框窗口模式】启动游戏'
  link: './fullscreen-windowed/launching'
description: Overlay Mode displays the map client over the Genshin game window. This mode benefits players who only have one monitor, allowing quicker switching between the game and the map client.
---

[文：【覆盖模式】使用说明]: # 'https://support.qq.com/products/321980/faqs/97047'

# 【覆盖模式】使用说明

## 功能介绍

覆盖模式是指<span style="color: green"><b>地图窗口</b></span>完全覆盖<span style="color: red"><b>游戏窗口</b></span>的模式，方便单屏幕玩家快速打开地图查看标记~

![](/imgs/manual/overlay-mode/1.png)
(客户端覆盖在游戏窗口上)

## 使用说明

- 该模式仅能在游戏非全屏模式下运行。
- 习惯全屏的玩家可以查看[【无边框窗口全屏模式】](./fullscreen-windowed/launching.md)教程，即可全屏打开覆盖模式
- 如果全屏模式运行游戏，将不能呼出地图（这时可在游戏内设置为窗口模式，或关闭游戏即可显示地图）
- 快捷键 Alt+Enter 也可以在保持分辨率的情况下快速切换窗口模式。
- 当点击按钮打开覆盖模式时，系统会出现覆盖模式开启提示。

![](/imgs/manual/overlay-mode/2.png)
(开启成功的提示)

- 开启覆盖模式后，【按下 Alt+M】、【按下 M】、【按下 Esc】、【点击界面右上角关闭按钮】，均可隐藏地图窗口回到游戏

![](/imgs/manual/overlay-mode/3.png)
(回到游戏界面的关闭按钮)

- 回到游戏后会发现小地图左侧出现派蒙图标即为开启成功。
- 如果没有出现小派蒙，说明悬浮窗异常加载，可能由于系统阻拦未能自动开启，此时可以手动开启悬浮窗插件，位置 `地图目录\Map_Data\Plugins\x86_64\tips.exe`

![](/imgs/manual/overlay-mode/4.png)
(派蒙图标)

- 开启成功后，在游戏内使用鼠标拖动小派蒙可移动其位置。
- 【双击派蒙图标】或者【按 Alt+m】均可返回大地图（ps.空格右边也有一个 alt）
- 在系统托盘里有小派蒙图标，右键可以自定义设置呼出按键

![](/imgs/manual/overlay-mode/5.png)
(修改呼出按键)

- 若无法正常开启功能，可能是由于防火墙屏蔽导致，我们也许能在不久后的版本修复这个问题。

## 常见问题

- 如果由于修改过呼出快捷键，导致快捷键冲突（例如修改为【Alt+Tab】）
- 可能导致快捷键无法呼出地图，或系统右下角托盘中，派蒙图标消失。
- 出现以上问题，可在【设置 - 常规 - 覆盖模式按键缓存目录】中，定位到覆盖模式按键缓存目录，删除目录下（【PopTips】文件夹）的所有文件。
- 重启后即可还原覆盖模式快捷键为 【Alt+M】

![](/imgs/manual/overlay-mode/6.png)
