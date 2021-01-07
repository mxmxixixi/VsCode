### 字体

> 下载 Fira code 字体，进行安装，vscode 中设置 Font Family 增加 Fira code

### 命令行

> Command + shift + p 之后 shell 选择安装 code 命令，可以在 iterm 中使用命令 code . 直接打开当前文件夹在 vscode 中

### 主题

> One Dark Proz

### EditorConfig for VS Code 插件

> 项目中使用此插件可以统一编码风格,比如代码空格数，此文件.editorconfig 放在项目根目录下面

```javascript
# http://editorconfig.org
root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

[*.md]
trim_trailing_whitespace = false

[Makefile]
indent_style = tab


```
