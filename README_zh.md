<div align="center">
  <a href="README.md">English</a> &nbsp;|&nbsp;
  <a href="README_zh.md"><b>简体中文</b></a> &nbsp;|&nbsp;
  <a href="README_ja.md">日本語</a> &nbsp;|&nbsp;
  <a href="README_ko.md">한국어</a>
</div>

<br>

# 🌍 走哪啦 (ZounaLa) · 社区多语言协作项目

> **协助完善多国语言表达，打造地道本土化体验，免费领取「Ultimate 终身会员」！** 🎁

---

## 📱 项目简介

![走哪啦多语言界面对比](localization.png)

**走哪啦 (ZounaLa)** 是一款注重绝对隐私、坚持零独立服务器架构的 iOS 生活痕迹与 Moment 记录应用，专为生活漫步者、户外探索者与回忆收藏家打造，记录日常足迹、发呆时光与亲密空间的美好瞬间。

为了给全球更多国家和地区的用户带来温暖、地道的使用体验，我们希望将应用内的每个按钮、副标题、提示文案和小组件都打磨得更加自然流畅——无论是 **韩语 (한국어)**、**日语 (日本語)** 还是 **英语 (English)**。

---

## 🎯 为什么需要您的协助

机器翻译虽然能提供基础参考，但唯有母语使用者才能捕捉到最契合当地文化语境、自然而有温度的表达方式：

- **特色词汇本土化**：如何在韩文或日文中更地道、优美地表达“发呆时光”、“足迹打卡”、“亲密空间”等特色概念。
- **UI 界面文字精炼**：确保翻译文案在手机屏幕按钮、锁屏小组件、通知弹窗中简洁优雅、不超长折行。
- **系统权限清晰表达**：准确、友好地解释相机、相册、地理位置及蓝牙等系统权限的使用目的。

---

## 🎁 贡献者奖励：免费赠送「Ultimate 终身会员」

每一份用心的翻译与校对都至关重要！为了表达我们的由衷谢意：

✨ **凡是提交的 Pull Request（或有价值的多语言改进建议）经团队审核合并（Approval），我们将免费赠送一份价值 $24.99+ 的「走哪啦 Ultimate 终身会员」永久激活码！**

### 🔑 如何领取您的专属激活码：
1. **获取您的账户 ID**：
   - 在 iPhone 上打开 **走哪啦 (ZounaLa)** App；
   - 进入 **设置** ➔ **Ultimate 会员激活**；
   - 点击 **您的账户 ID**（界面显示的 8 位字符，如 `886333C5`）完成一键复制。
2. **在 PR / Commit 中附带信息**：
   - 提交 Pull Request 时，请在 **PR 说明**（或 Commit 提交信息）中附上：
     - **您的 8 位账户 ID**：（例如 `Account ID: 886333C5`）
     - **您的接收邮箱**：（例如 `Email: yourname@example.com`）
3. **通过邮件查收激活码**：
   - 团队审核并合并您的 PR 后，会立即为您生成专属的 Ultimate 终身激活码，并直接发送到您填写的邮箱中！

---

## 📂 待编辑的语言包文件

本项目核心需要编辑的文件为：

- [`Localizable.xcstrings`](Localizable.xcstrings) — 苹果官方标准的 **Xcode String Catalog**（JSON 格式），包含 **英语 (`en`)**、**韩语 (`ko`)**、**日语 (`ja`)** 及 **简体中文 (`zh-Hans`)** 的全量文案词条。

---

## 🛠 如何参与贡献

### 方式一：使用 Xcode（推荐 iOS 开发者）
1. Fork 并克隆本仓库到本地；
2. 在 **Xcode 15 或更高版本** 中打开 [`Localizable.xcstrings`](Localizable.xcstrings)；
3. 利用 Xcode 可视化 String Catalog 编辑器筛选未翻译或需要优化的词条，直接修改并保存；
4. 提交 Commit 并发起 Pull Request。

### 方式二：使用任意代码/文本编辑器（VS Code、Cursor、Sublime 等）
1. Fork 并克隆本仓库；
2. 使用您喜欢的文本/JSON 编辑器打开 [`Localizable.xcstrings`](Localizable.xcstrings)；
3. 找到目标词条下对应的语言键（如 `"ko"`、`"ja"`、`"en"`），修改 `"value"` 字段；
4. 确保 JSON 格式合法无误；
5. 提交 Commit 并发起 Pull Request。

### 方式三：直接提交 Issue
如果您不熟悉 Git/PR 操作：
1. 前往 [GitHub Issues](https://github.com/zouna-la/localization/issues) 新建一个 Issue；
2. 详细列出原文（中文/英文键名）以及您建议的该语言地道翻译；
3. 附带您的 **Account ID** 与 **联系邮箱**，以便我们在采纳后为您发送 Ultimate 会员奖励！

---

## 💡 翻译规范与建议

- **保留格式占位符**：请务必保留文案中的变量占位符（例如 `%@`、`%lld`、`%1$@`、`%2$@`、`%d` 等），确保动态数值与日期正常渲染。
- **保持移动端精炼**：手机界面空间有限，建议在表达精准的基础上力求精炼，避免生硬直译导致的文字过长。
- **温暖温和的语调**：走哪啦是一款具有人文温度的生活记录伴侣，建议采用温和、积极、礼貌的语调。

---

## 🤝 疑问与交流

如果您对某些特定功能场景的上下文有疑问，欢迎随时创建 [GitHub Issue](https://github.com/zouna-la/localization/issues) 进行交流讨论。

感谢每一位帮助「走哪啦」走向世界、变得更好的开发者与朋友！❤️
