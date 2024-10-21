# Claude.ai Translator

## 简介
Claude.ai 汉化 是一个 Tampermonkey 脚本，用于将 Claude.ai 网站界面翻译成中文。这个脚本可以自动翻译固定的 UI 元素，同时保持网站的布局和功能不变。 （全部代码由Claude编写）

## 功能
- 自动将 Claude.ai 的界面元素翻译成中文
- 保留原有的网站布局和功能
- 使用 Google Translate API 自动翻译claude生成的标题
- 为了提高体验，翻译结果会缓存，可以在左侧清除缓存

## 安装
1. 确保您的浏览器已安装 Tampermonkey 扩展
2. 点击 [这里](https://greasyfork.org/zh-CN/scripts/513360-claude-ai-%E6%B1%89%E5%8C%96) 安装脚本，或直接下载本项目的js文件
3. Tampermonkey 会自动打开一个新的标签页，显示脚本的源代码
4. 点击 "安装" 或 "更新" 按钮

## 使用方法
安装脚本后，只需访问 [Claude.ai](https://claude.ai/) 网站，界面就会自动翻译成中文。

### 清除缓存
在侧边栏底部，您会看到一个 "清除缓存" 按钮。点击此按钮可以清除所有缓存的翻译结果。

## 自定义
如果您想添加或修改翻译，可以编辑脚本中的 `translations` 对象。

## 注意事项
- 此脚本不会翻译用户输入的内容或 Claude 的回复
- 某些动态加载的内容可能需要一些时间才能被翻译
- 使用 Google Translate API 可能会有流量限制，请谨慎使用

## 贡献
欢迎提交 Pull Requests 来改进翻译或添加新功能。

## 免责声明
本脚本仅供学习和个人使用。作者不对因使用此脚本造成的任何问题负责。请遵守 Claude.ai 的使用条款。
