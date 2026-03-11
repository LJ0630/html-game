# HTML 网页游戏合集

一个包含多个经典小游戏的网页游戏项目，使用原生 HTML、CSS 和 JavaScript 开发。

## 游戏列表

### 🐍 贪吃蛇 (Snake)

经典的手机游戏，玩家控制一条蛇通过吃食物来增长自己的身体长度，同时避免撞到墙壁或自己的身体。

**功能特性：**
- 键盘控制（方向键或 WASD）
- 本地最高分存储
- 霓虹风格视觉效果
- 流畅的动画效果

**如何开始：**
直接在浏览器中打开 `snake.html` 文件即可开始游戏。

---

### ♟️ 五子棋 (Gomoku)

经典的棋类游戏，玩家轮流在 15×15 的棋盘上落子，率先实现五子连珠（横、竖、斜任意方向）获胜。

**功能特性：**
- 人人对战模式
- 人机对战模式（智能 AI）
- 悔棋功能
- 游戏计时器
- 落子历史记录
- 对局统计数据
- 鼠标悬停预览
- 落子动画效果
- 胜负判定提示

**如何开始：**
直接在浏览器中打开 `gomoku.html` 文件即可开始游戏。

---

## 技术栈

- **HTML5** - 游戏结构
- **CSS3** - 样式与动画
- **JavaScript (ES6+)** - 游戏逻辑
- **Canvas API** - 棋盘绘制

## 运行方式

### 本地运行

1. 克隆仓库：
```bash
git clone https://github.com/LJ0630/html-game.git
```

2. 进入项目目录：
```bash
cd html-game
```

3. 直接用浏览器打开对应的 HTML 文件即可游玩

### 使用本地服务器

如果你想要通过本地服务器运行：

```bash
# Python 3
python -m http.server 8000

# 或者 Node.js
npx http-server
```

然后访问 `http://localhost:8000`

---

## 游戏截图

### 贪吃蛇
![Snake Game](screenshots/snake.png)

### 五子棋
![Gomoku Game](screenshots/gomoku.png)

---

## 浏览器兼容性

| 浏览器 | 最低版本 |
|--------|----------|
| Chrome | 80+ |
| Firefox | 75+ |
| Safari | 13+ |
| Edge | 80+ |

---

## 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

---

## 许可证

本项目仅供学习交流使用。

---

Made with ❤️
