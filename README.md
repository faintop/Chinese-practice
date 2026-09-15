# 中文26键打字训练系统

适用于电脑 QWERTY 实体键盘的中文打字练习工具，使用单个 HTML 文件实现，无需安装依赖。

## 使用方式

下载本仓库的 `index.html`，用 Edge、Chrome 等浏览器打开即可练习。也可以在仓库页面选择 Code → Download ZIP，解压后打开 `index.html`。

## 训练内容

- 可视化指法教学：查看字母对应手指及回位键。
- 键位训练：基准排、全部字母和易错键练习。
- 拼音训练：使用英文输入状态输入拼音。
- 中文词语：使用系统中文拼音输入法选择汉字。
- 文章练习：逐字反馈、准确率、速度和进度。
- 练习记录：在当前浏览器本地保存完成记录和易错键。

## 数据说明

练习记录存储在浏览器 localStorage 中，不会上传到 GitHub，也不会跨设备自动同步。清除浏览器数据会删除记录。本地文件和在线站点的记录彼此独立。

## 修改和发布

主要页面、样式和脚本均位于 `index.html`。修改后重新用浏览器打开即可。

### GitHub Pages 发布

仓库已准备好静态发布入口 `index.html` 和 `.nojekyll`。仍需仓库管理员首次启用 Pages：

1. 打开 https://github.com/faintop/Chinese-practice/settings/pages 。
2. 在 Build and deployment 下，将 Source 设为 Deploy from a branch。
3. 将 Branch 设为 main，目录设为 / (root)，点击 Save。
4. 等待 GitHub Pages 部署完成，使用设置页的 Visit site 验证首页能打开。

启用并部署成功后的预期分享地址：https://faintop.github.io/Chinese-practice/

以上地址不是已上线状态的保证；请以 Pages 设置页和实际打开结果为准。访问者无需 GitHub 或 ChatGPT 账号。首次发布可能需要约 10 分钟。

启用后，提交到 main 的网页更新会触发 Pages 发布。GitHub 与 Sites 之间没有配置自动部署，更新此仓库不会自动更新 Sites 网站。

可在仓库首页 About 旁的齿轮中，将 Website 填为上述已验证的网站地址。

### 访问和源码

此发布方案优先满足免费在线访问和分享，不保证中国大陆网络的可达性。训练器为纯前端网页，没有外部脚本或字体依赖，下载后也可以离线使用。

仓库当前公开。分享网站地址会直接显示训练器，但网页运行所需的 HTML、CSS 和 JavaScript 仍可被浏览器查看。更换托管平台或隐藏仓库不能完全隐藏这些前端代码。

