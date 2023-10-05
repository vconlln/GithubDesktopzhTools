# GithubDesktopzhTools

本仓库为GitHubDesktop汉化工具。

GitHubDesktop官网：[https://desktop.github.com](https://desktop.github.com/) 

注：遇到汉化失败，重试一下子。

意：请一定保持Github Desktop版本与本汉化工具版本对应，否则汉化后Github Desktop可能会打不开。

### Windows汉化

打开GithubDesktopZhTool.exe，点击汉化即可。

### Mac汉化

将本仓库中Mac文件夹下的main.js和renderer.js拷贝替换本地GithubDesktop的资源目录

本地GithubDesktop资源目录一般为： `/Applications/GitHub Desktop.app/Contents/Resources/app` 

### Linux汉化

Linux版GithubDesktop仓库：https://github.com/shiftkey/desktop

将本仓库中`Linux`文件夹下的`main.js`和`renderer.js`复制替换本地`GithubDesktop`的资源目录

可以食用命令看一下指向的目录

```shell
where github-desktop
ls -l /usr/bin/github-desktop
/usr/bin/github-desktop -> /opt/github-desktop/github-desktop
```

替换两个文件即可

```shell
sudo cp main.js renderer.js /opt/github-desktop/resources/app
```

