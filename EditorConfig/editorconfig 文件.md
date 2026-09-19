# editorconfig 文件

`.editorconfig` 文件用于统一不同编辑器的基础编辑规则，减少不同开发环境之间的文件内容格式差异

# 配置说明

| 配置项                   | 值    | 说明                                    |
|--------------------------|-------|-----------------------------------------|
| root                     | true  | 将当前 `.editorconfig` 作为项目配置的根 |
| charset                  | utf-8 | 使用 UTF-8 字符编码                     |
| indent_size              | 4     | 设置一个缩进级别的宽度为 4              |
| indent_style             | space | 使用空格作为缩进方式                    |
| end_of_line              | lf    | 使用 LF 作为换行符                      |
| insert_final_newline     | true  | 文件末尾保留一个换行符                  |
| trim_trailing_whitespace | true  | 删除行尾的空白字符                      |

# 配置规则

编辑项目根目录中的 `.editorconfig`：

```editorconfig
root = true

[*]
charset = utf-8
indent_size = 4
indent_style = space
end_of_line = lf
insert_final_newline = true
trim_trailing_whitespace = true
```


