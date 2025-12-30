# Markdown 与 HTML 双向转换器

一个简洁高效的 Markdown 和 HTML 双向转换工具，支持富文本编辑、实时预览和暗色模式。

## 功能特性

- **双向转换**：Markdown ↔ HTML 无缝转换
- **实时预览**：输入时自动检测并显示预览
- **富文本编辑**：内置 Quill 编辑器，支持格式化编辑
- **暗色模式**：一键切换深色/浅色主题
- **响应式设计**：完美适配桌面和移动设备
- **快捷键支持**：`Ctrl + Enter` 快速转换

## 使用方法

### 在线使用

直接在浏览器中打开 `index.html` 文件即可使用。

### 本地运行

```bash
# 使用 Python
python -m http.server 8000

# 或使用 npx
npx serve .
```

然后访问 `http://localhost:8000`

## 界面说明

### 代码转换

1. 在左侧输入框输入 Markdown 或 HTML 代码
2. 点击对应按钮进行转换：
   - **Markdown 转 HTML**：将 Markdown 转换为 HTML
   - **HTML 转 Markdown**：将 HTML 转换为 Markdown
3. 右侧预览区显示渲染效果
4. 底部输出框显示转换后的代码，可复制使用

### 富文本编辑

1. 切换到"富文本编辑"标签
2. 使用工具栏进行格式化编辑
3. 点击按钮导出为 Markdown 或 HTML

## 键盘快捷键

| 快捷键 | 功能 |
|--------|------|
| `Ctrl + Enter` | 快速转换 |

## 技术栈

- **marked** (v2.0.3) - Markdown 解析
- **turndown** (v7.1.1) - HTML 转 Markdown
- **Quill** (v1.3.6) - 富文本编辑器

## 项目结构

```
mv/
├── index.html    # 主应用文件
├── README.md     # 项目说明
└── AGENTS.md     # 开发规范
```

## 浏览器支持

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## 许可证

MIT License
