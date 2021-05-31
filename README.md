# `GreasyFork Scripts`

- ## **Font Rendering.user.js** (`version 2021.04.04.2`)

  简介：让每个页面的字体变得有质感，默认使用苹方字体，附加字体描边、字体阴影、字体平滑等效果，自用脚本不处理外部需求。

  > `version 2021.04.04.2`

  ```text
  + MutationObserver callback()函数优化，对所有站点启用。
  @ 默认值的重新设定。
  ```

- ## **Google & Baidu Switcher.user.js** (`version 2.5.20210601.2`)

  简介：最新版本的集合谷歌、百度、必应的搜索引擎跳转工具，必应跳转可在菜单进行自定义设置。此版本无外部脚本调用，更快速和准确的进行按钮定位，显示速度大大提升。如有异常请清空浏览器缓存，再次载入使用，感谢使用！

  > `version 2.5.20210601.2`

  ```text
  + 增加脚本菜单栏“更新检查”选项。
  @ 重构GM_notification函数，不再使用默认系统对话框，访问同一域名的更新检查提示最多2次（关闭页面后重新计数）。
  @ 修正Firefox不能自动关闭弹出窗口的bug.
  @ 优化版本对比算法。
  ! 该版本为重大更新，请及时完成新版的覆盖安装。
  ```

- ## **PowerlinePro.psm1** (`version 1.0.0`)

  简介：Powershell Themes - 修正原版的错误，添加部分功能，字体建议使用 *"Sarasa Term SC"*，字号 *"14"*。

  <sub>**VSCode 配色**</sub>

    ```json
    "workbench.colorCustomizations": {
      "terminal.background": "#FFFFFF",
      "terminal.foreground": "#4e5258",
      "terminalCursor.background": "#6a7586",
      "terminalCursor.foreground": "#134979",
      "terminal.ansiBlack": "#FFFFFF",
      "terminal.ansiBlue": "#3971ED",
      "terminal.ansiBrightBlack": "#B4B7B4",
      "terminal.ansiBrightBlue": "#677fb6",
      "terminal.ansiBrightCyan": "#33353a",
      "terminal.ansiBrightGreen": "#198844",
      "terminal.ansiBrightMagenta": "#d2049b",
      "terminal.ansiBrightRed": "#CC342B",
      "terminal.ansiBrightWhite": "#e2e8ee",
      "terminal.ansiBrightYellow": "#FBA922",
      "terminal.ansiCyan": "#3971ED",
      "terminal.ansiGreen": "#198844",
      "terminal.ansiMagenta": "#A36AC7",
      "terminal.ansiRed": "#CC342B",
      "terminal.ansiWhite": "#373B41",
      "terminal.ansiYellow": "#FBA922"
    }
    ```
