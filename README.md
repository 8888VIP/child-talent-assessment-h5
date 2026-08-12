# 儿童天赋测评 H5

纯 HTML/CSS/JavaScript 单文件移动端应用。直接双击 `index.html` 即可运行，无需服务端与第三方依赖。

## 功能

- 快速版：16 题、八大智能简明报告
- 精准版：48 题、八大智能雷达图、性格偏好、霍兰德兴趣、交叉分析
- 快速版升级精准版时自动带入已答 16 题
- `localStorage` 自动保存资料与作答进度
- 320–480px 手机宽度适配
- 关于页、重新测评、截图保存提示

## 本地预览

```powershell
Start-Process .\index.html
```

也可以在目录运行静态服务器：

```powershell
python -m http.server 4173
```

然后访问 `http://localhost:4173/`。
