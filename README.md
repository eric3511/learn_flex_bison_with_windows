# 说明:

## flex 使用方法
- 打开Developer PowerShell for VS20XX 或 x64 Native Tools Command Prompt for VS 20XX
- win_flex.exe --wincompat --outfile=fb1-1.c fb1-1.l
- cl.exe fb1-1.c


## visual studio 集成 flex&&bison

- 配置 自定义生成 https://github.com/lexxmark/winflexbison/blob/master/custom_build_rules/README.md
- 更改项目的c++ 属性 C/C++ -> 语言 -> 符合模式 -> 否/Permissive (放任模式,允许 不严格的检查)


 