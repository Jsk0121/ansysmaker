# GitHub Pages 上传说明

这个文件夹里的文件就是网页版本需要上传到 GitHub 的文件。

## 最简单用法

1. 在 GitHub 新建一个仓库。
2. 把本文件夹里的 `index.html` 和 `.nojekyll` 上传到仓库根目录。
3. 打开仓库 Settings -> Pages。
4. Source 选择 Deploy from a branch。
5. Branch 选择 main，Folder 选择 /root。
6. 保存后等待 GitHub Pages 生成网址。

## 打开网页后怎么用

1. 输入 API Base URL，例如 `https://api.openai.com/v1`。
2. 输入 API Key。
3. 输入模型名。
4. 填写工程描述或上传资料。
5. 点击生成。

注意：这是纯前端网页，API Key 会在浏览器中使用，不要把 API Key 写进 `index.html`。
