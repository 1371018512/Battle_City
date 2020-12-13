# 游戏简介

### 技术栈介绍

本游戏未使用任何框架，用 js、css 以及 html 的 canvas 实现
郑鉴测试

### 界面构成

由五个 canvas 画板叠加构成：

1. wallCanvas
2. tankCanvas
3. grassCanvas
4. overCanvas
5. stageCanvas // 菜单和过关场景共用的画布

### 项目结构

```
├── audio
│ ├── attack.mp3
│ ├── bulletCrack.mp3
│ ├── move.mp3
│ ├── playerCrack.mp3
│ ├── prop.mp3
│ ├── start.mp3
│ └── tankCrack.mp3
├── css
│ └── default.css
├── images
│ ├── Thumbs.db
│ ├── menu.gif
│ └── tankAll.gif
├── index.html
├── js
│ ├── Collision.js //碰撞相关
│ ├── Helper.js // 修改原生数组
│ ├── bullet.js // 子弹实体
│ ├── const.js // 一些全局变量
│ ├── crackAnimation.js //爆炸实体以及爆炸绘制的方法
│ ├── jquery.min.js
│ ├── keyboard.js // 记录键盘对应编号
│ ├── level.js // 关卡地图信息
│ ├── main.js // 主函数
│ ├── map.js // 游戏界面相关
│ ├── menu.js // 开始菜单实体
│ ├── num.js
│ ├── prop.js
│ ├── stage.js // 过关过场,包含拉开和合上幕布的动画以及中间字幕
│ └── tank.js // 坦克实体以及坦克行为
└── readme.md
```

# 游戏原理
