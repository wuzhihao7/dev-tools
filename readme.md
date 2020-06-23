# java开发规范
## 代码规范
1. 使用google java code style，IDE统计format格式
2. 文件编码：UTF-8
3. 文件换行符：unix（LF）
## Git规范
1. 拒绝提交包含混合换行符的文件：git config --global core.safecrlf true
2. 提交时转换为LF，检出时不转换：git config --global core.autocrlf input