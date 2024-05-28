# 如何远程连接到开发板

## 配置网络

1. 安装ZeroTier One.msi，[下载地址](https://www.zerotier.com/download/)
1. 安装成功加入网路`e26ff13e35c02360`
2. 告诉我你的My Address：例如:`24e9f2b6fb`

## 使用远程工具

1. 下载远程工具。[去下载](https://github.com/Genymobile/scrcpy/releases/download/v2.4/scrcpy-win64-v2.4.zip)
6. 解压缩`scrcpy-win64-v2.4.zip`
1. 下载命令行工具。[去下载](https://github.com/cmderdev/cmder/releases/download/v1.3.24/cmder_mini.zip)
3. 解压缩`cmder.zip`
4. 打开`Cmder.exe`
5. cd到`scrcpy-win64-v2.4`的目录。如：`cd C:\Users\ccc\Documents\scrcpy-win64-v2.4`
7. 执行`adb connect 10.100.105.36`
8. 执行`scrcpy -m 1024`
9. 就可以愉快的远程控制了
