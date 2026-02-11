# Stickers

<div align="center">

![GitHub License](https://img.shields.io/github/license/25-ji-code-de/stickers?style=flat-square&color=884499)
![GitHub stars](https://img.shields.io/github/stars/25-ji-code-de/stickers?style=flat-square&color=884499)
![GitHub forks](https://img.shields.io/github/forks/25-ji-code-de/stickers?style=flat-square&color=884499)
![GitHub issues](https://img.shields.io/github/issues/25-ji-code-de/stickers?style=flat-square&color=884499)
![GitHub last commit](https://img.shields.io/github/last-commit/25-ji-code-de/stickers?style=flat-square&color=884499)
![GitHub repo size](https://img.shields.io/github/repo-size/25-ji-code-de/stickers?style=flat-square&color=884499)
[![CodeFactor](https://img.shields.io/codefactor/grade/github/25-ji-code-de/stickers?style=flat-square&color=884499)](https://www.codefactor.io/repository/github/25-ji-code-de/stickers)

</div>

一个简单、轻量级的网页应用，用于展示 Project SEKAI 贴纸、表情包。使用原生 JavaScript 读取 JSON 配置文件，并动态渲染出响应式的图片网格。

## ✨ 特性

- 🎯 **动态加载** - 通过修改 `stickers.json` 即可添加或删除内容，无需修改 HTML 代码
- 📱 **响应式设计** - 采用 CSS Grid 布局，在手机和电脑上都能完美显示
- ⚡ **原生极简** - 没有复杂的依赖框架（如 React 或 Vue），打开速度快，易于修改
- 🖼️ **懒加载** - 支持图片 Lazy Loading，提升页面性能
- 🔍 **自动补全** - 支持贴纸搜索和自动补全功能

## 🚀 快速开始

### 本地运行

```bash
# 克隆仓库
git clone https://github.com/25-ji-code-de/stickers.git
cd stickers

# 使用任意 HTTP 服务器运行
python3 -m http.server 8000
# 或
npx serve
```

然后访问 `http://localhost:8000`

### 在线访问

🌐 **[https://sticker.nightcord.de5.net](https://sticker.nightcord.de5.net)**

## 📁 项目结构

```
stickers/
├── index.html           # 主页面
├── stickers.json        # 贴纸数据配置
├── autocomplete.json    # 自动补全数据
└── stickers/            # 贴纸图片资源
    ├── miku/
    ├── rin/
    ├── len/
    └── ...
```

## 🛠️ 技术栈

- **前端**: 原生 HTML + CSS + JavaScript
- **部署平台**: Cloudflare Pages
- **图片格式**: PNG

## 🌐 SEKAI 生态

本项目是 **SEKAI 生态**的一部分。

查看完整的项目列表和架构：**[SEKAI 门户](https://sekai.nightcord.de5.net)**

---

**声明**：本项目受 *Project SEKAI COLORFUL STAGE! feat. Hatsune Miku* 启发。

本项目是非官方、非商业性质的粉丝作品，与 SEGA、Colorful Palette、Crypton Future Media 或任何其他与《Project SEKAI》相关的版权持有方无任何官方关联。

所有游戏相关素材（包括但不限于角色、音乐、图像）的版权归其各自的版权持有方所有。

## 🤝 贡献

欢迎贡献！我们非常感谢任何形式的贡献。

在贡献之前，请阅读：
- [贡献指南](./CONTRIBUTING.md)
- [行为准则](./CODE_OF_CONDUCT.md)

## 🔒 安全

如果发现安全漏洞，请查看我们的 [安全政策](./SECURITY.md)。

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](./LICENSE) 文件。

⚠️ **重要提示**：MIT 许可证仅适用于本项目的原创代码。游戏相关素材（贴纸图像等）的版权归 SEGA、Colorful Palette、Crypton Future Media 等原版权方所有。

## 📧 联系方式

- **GitHub Issues**: [https://github.com/25-ji-code-de/stickers/issues](https://github.com/25-ji-code-de/stickers/issues)
- **项目主页**: [https://sticker.nightcord.de5.net](https://sticker.nightcord.de5.net)
- **哔哩哔哩**: [@bili_47177171806](https://space.bilibili.com/3546904856103196)

## 🙏 致谢

- 感谢所有贡献者
- 感谢 Project SEKAI 提供的精美贴纸素材

## ⭐ Star History

如果这个项目对你有帮助，请给我们一个 Star！

[![Star History Chart](https://api.star-history.com/svg?repos=25-ji-code-de/stickers&type=Date)](https://star-history.com/#25-ji-code-de/stickers&Date)

---

<div align="center">

**[SEKAI 生态](https://sekai.nightcord.de5.net)** 的一部分

Made with 💜 by the [25-ji-code-de](https://github.com/25-ji-code-de) team

</div>
