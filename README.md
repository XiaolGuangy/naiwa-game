# 奶蛙大作战 · 寒武风云

一款文亚宇宙同人横版动作游戏。人物与情节为虚构创作，与现实人物没有隶属关系。

**在线游玩：** https://xiaolguangy.github.io/naiwa-game/

## 操作

- 手机：横屏游玩；左侧按住并左右滑动移动，松手停止。右侧按键分别为大招、冲刺、奶弹、跳跃和攻击，支持双手同时操作。
- 电脑：A/D 或方向键移动，空格跳跃，J 攻击、K 奶弹、L 冲刺、I 大招，Esc 暂停。
- 具体规则和其他按键见游戏内「操作说明」。

## 在本地运行

这是静态网页，无需构建。可以用任意静态文件服务器提供此目录，例如 `python -m http.server 8000`，然后访问 `http://localhost:8000/`。

## 检查移动端交互

安装 Node.js 后运行 `npm install` 和 `npx playwright install chromium`，然后运行 `npm test`。如使用已安装的 Chromium 浏览器，可以设置 `BROWSER_PATH` 指向浏览器可执行文件。

## 授权与素材

游戏代码采用 [MIT 许可证](LICENSE)。`assets/` 下的人物照片、音频及其他素材可能涉及第三方权利，不包含在代码的 MIT 许可范围内；再次使用前请自行核实并取得所需授权。项目发布者确认已取得本项目公开发布所需许可。

部分人物图片参考了 [李文亚 Wiki](https://github.com/bdydgz114514/bdydgz114514.github.io)、[李文亚知识库](https://github.com/bdydgz114514/liwenya-kb) 和 [Professor-Wenya-Li-Meme](https://github.com/459zyt/Professor-Wenya-Li-Meme) 中的公开素材；原素材的权利归相应权利人所有。
