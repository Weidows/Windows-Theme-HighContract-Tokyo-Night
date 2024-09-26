---
title: 🏳️‍🌈Windows-Theme-HighContract-Tokyo-Night
password: ""
tags:
  - Windows
  - theme
katex: false
comments: true
aside: true
date: 2023-11-20 17:08:04
cover: https://pan.weidows.tech/d/local/blog/owlk10.png
top_img:
---

# Windows-Theme-HighContract-Tokyo-Night

<!--
 * @?: *********************************************************************
 * @Author: Weidows
 * @LastEditors: Weidows
 * @LastEditTime: 2024-08-06 15:44:32
 * @FilePath: \Blog-private\source\_posts\system\Windows-Theme-HighContract-Tokyo-Night\README.md
 * @Description:
 * @!: *********************************************************************
-->

{% pullquote mindmap mindmap-sm %}

- [Windows-Theme-HighContract-Tokyo-Night](#windows-theme-highcontract-tokyo-night)
  - [Preview](#preview)
  - [Feature](#feature)
  - [安装](#安装)
    - [手动](#手动)
    - [Scoop](#scoop)
  - [借物表](#借物表)

{% endpullquote %}

<a>![分割线](https://pan.weidows.tech/d/local/img/divider.png)</a>

## Preview

![owlrlm.png](https://pan.weidows.tech/d/local/blog/owlrlm.png)

![owlk10.png](https://pan.weidows.tech/d/local/blog/owlk10.png)

![owluuT.png](https://pan.weidows.tech/d/local/blog/owluuT.png)

<a>![分割线](https://pan.weidows.tech/d/local/img/divider.png)</a>

## Feature

- [x] 一键安装
  - [ ] 本来想用 .themepack 打包, 遇到点问题
- [x] 原神音效
- [x] 拉扬白光标
- [x] 极高对比度
  - [ ] 可惜系统对某些组件的显示效果支持不好

---

## 安装

### 手动

下载 Release 中压缩包-解压-右键管理员模式运行 `install.bat`

然后设置-个性化-主题里会出现新的主题, 点一下就 OK

卸载的话, 同上运行 `uninstall.bat`

---

### Scoop

```
scoop bucket add apps https://github.com/kkzzhizhou/scoop-apps
scoop install Windows-Theme-HighContract-Tokyo-Night
```

---

## customize

`[Control Panel\Colors]` 这些键及其对应的 RGB 颜色值用于定义 Windows 经典主题中各种界面的颜色元素。下面解释每个键对应的具体界面部分：

1. **ActiveTitle=10 36 106**
   **激活窗口的标题栏背景颜色**。当窗口处于激活状态（选中）时，标题栏的背景颜色。

2. **Background=166 202 240**
   **桌面背景颜色**。这定义了桌面上未被任何窗口或图标覆盖的区域的颜色。

3. **Hilight=10 36 106**
   **选中项目的背景颜色**。当你在文件资源管理器中选中一个文件或选项时，背景高亮显示的颜色。

4. **HilightText=255 255 255**
   **选中项目的文本颜色**。文件或选项被选中时，文本的颜色。

5. **TitleText=255 255 255**
   **激活窗口的标题栏文字颜色**。窗口标题栏上的文字颜色，当窗口处于激活状态时。

6. **Window=255 255 255**
   **窗口背景颜色**。窗口内容区域的背景颜色，例如记事本的空白区域。

7. **WindowText=0 0 0**
   **窗口文本颜色**。窗口中正常显示文本的颜色，比如记事本中的文字。

8. **Scrollbar=212 208 200**
   **滚动条背景颜色**。滚动条轨道的颜色。

9. **InactiveTitle=128 128 128**
   **非激活窗口的标题栏背景颜色**。当窗口处于非激活状态（未选中）时，标题栏的背景颜色。

10. **Menu=212 208 200**
    **菜单背景颜色**。窗口菜单（如右键菜单或文件菜单）的背景颜色。

11. **WindowFrame=0 0 0**
    **窗口边框颜色**。窗口的外框颜色。

12. **MenuText=0 0 0**
    **菜单文本颜色**。菜单中显示文字的颜色。

13. **ActiveBorder=212 208 200**
    **激活窗口的边框颜色**。当窗口被选中时，边框的颜色。

14. **InactiveBorder=212 208 200**
    **非激活窗口的边框颜色**。当窗口未被选中时，边框的颜色。

15. **AppWorkspace=128 128 128**
    **应用程序工作区背景颜色**。当多个文档窗口处于 MDI 应用程序（多文档界面）中时，非活动窗口之间的区域颜色。

16. **ButtonFace=212 208 200**
    **按钮的表面颜色**。按钮的背景颜色，例如 "确定" 或 "取消" 按钮的表面。

17. **ButtonShadow=128 128 128**
    **按钮的阴影颜色**。按钮阴影部分的颜色，通常是边缘或下部的颜色，给人一种 3D 效果。

18. **GrayText=128 128 128**
    **禁用文本颜色**。当文本处于禁用状态时（比如按钮不可点击时），显示为灰色的文字颜色。

19. **ButtonText=0 0 0**
    **按钮文字颜色**。按钮上显示的文字的颜色。

20. **InactiveTitleText=212 208 200**
    **非激活窗口的标题栏文字颜色**。当窗口未被选中时，标题栏的文字颜色。

21. **ButtonHilight=255 255 255**
    **按钮高光颜色**。按钮高光部分的颜色，通常是按钮顶部或侧面的高光区域，给人一种 3D 效果。

22. **ButtonDkShadow=64 64 64**
    **按钮深色阴影**。按钮的深色阴影，通常在按钮的底部或右侧，增强 3D 效果。

23. **ButtonLight=212 208 200**
    **按钮浅色部分**。按钮的浅色部分，通常用于边缘，帮助增强按钮的视觉效果。

24. **InfoText=0 0 0**
    **工具提示文本颜色**。工具提示窗口中显示的文本颜色。

25. **InfoWindow=255 255 225**
    **工具提示背景颜色**。工具提示窗口的背景颜色。

26. **GradientActiveTitle=166 202 240**
    **激活窗口的渐变标题栏颜色**。当启用渐变效果时，激活窗口标题栏的颜色变化。

27. **GradientInactiveTitle=192 192 192**
    **非激活窗口的渐变标题栏颜色**。当窗口未激活并且启用渐变效果时，标题栏的颜色变化。

<a>![分割线](https://pan.weidows.tech/d/local/img/divider.png)</a>

## 借物表

> 请去支持各位原作者, 至少点个赞

<a name='cite_note-1' href='#cite_ref-1'>[1]</a>: [原神游戏音效选集：七圣召唤更新](https://www.bilibili.com/video/BV1Ls4y1B7mB)

<a name='cite_note-2' href='#cite_ref-2'>[2]</a>: [拉扬白光标 - 图标指针 - 致美化](https://zhutix.com/ico/layan-white-cus/)

<a name='cite_note-3' href='#cite_ref-3'>[3]</a>: [东京之夜 Win11 主题 - 桌面主题 - 致美化](https://zhutix.com/pc/tokyo-night-vs/)

<a name='cite_note-4' href='#cite_ref-4'>[4]</a>: [自己动手做主题包](https://meta.appinn.net/t/topic/27800)

<a name='cite_note-5' href='#cite_ref-5'>[5]</a>: [GitHub - sapientcoder/CabMaker: CabMaker is a free Windows desktop tool that lets you quickly package up an entire folder of files (including subfolders) into a .cab file.](https://github.com/sapientcoder/CabMaker/) \
似乎只能 pack .theme, 不太好使
