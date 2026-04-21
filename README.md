# Gomoku 五子棋

一个简洁优雅的网页版五子棋游戏，使用原生 HTML、CSS 和 JavaScript 开发。

## 功能特性

- 15x15 标准棋盘
- 黑方白方交替落子
- 实时显示当前回合方
- 最后落子标记（红点提示）
- 自动判断胜负（横、竖、斜、反对角线五子连珠）
- 平局检测（棋盘填满）
- 重新开始功能

## 技术栈

- HTML5
- CSS3（Flexbox、Grid、渐变、阴影）
- JavaScript（原生 ES6+，无框架依赖）
- Google Fonts（Microsoft YaHei）

## 如何运行

直接用浏览器打开 `gomoku.html` 即可开始游戏：

```bash
# macOS
open gomoku.html

# Linux
xdg-open gomoku.html

# Windows
start gomoku.html
```

或双击文件在浏览器中打开。

## 游戏规则

1. 黑方先手，双方轮流落子
2. 任一方在横、竖、斜、反对角线方向连成五子即获胜
3. 棋盘填满且无人获胜则为平局

## 项目结构

```
gomoku-game/
├── README.md
└── gomoku.html    # 游戏主文件
```