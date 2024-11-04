# DDCS

DDCS，全称Docker Desktop Chinese Script，即Docker汉化脚本。

![](https://pic.imge.cc/2024/09/13/66e438a8ab768.jpg)

原仓库：【 https://github.com/asxez/DDCS 】

<big>**另外，原作者还发布了现成的 `app.asar` 可以在这个仓库找到各个版本的汉化包：【 https://github.com/asxez/DockerDesktop-CN 】**</big>


## 使用方法

> [!NOTE]
> 需要已安装 python3、Nodejs
> 

1. 关闭Docker Desktop
2. 下载源码，执行以下命令：

```bash
git clone https://github.com/fany0r/DDCS.git
cd DDCS
npm install
python3 ddcs.py
```
3. 替换 `app.asar`

> [!NOTE]
> Windows下默认为`C:\Program Files\Docker\Docker\frontend\resources`
> 
> MacOS下默认为`/Applications/Docker.app/Contents/MacOS/Docker Desktop.app/Contents/Resources`

~~注意：请务必使用管理员权限启动终端。~~
