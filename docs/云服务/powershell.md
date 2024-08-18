# powershell 常用命令

## 环境变量

```shell
# 设置环境变量(临时)
$env:VAR_NAME="value"

## 设置环境变量(永久)
[System.Environment]::SetEnvironmentVariable("VAR_NAME", "value", [System.EnvironmentVariableTarget]::User)

## 要将值为 Bar 的新环境变量 Foo 保存到计算机作用域
[Environment]::SetEnvironmentVariable('Foo', 'Bar', 'Machine')

# 查看环境变量
$env:path

## 查看环境变量
Get-ChildItem -Path Env:\
```
