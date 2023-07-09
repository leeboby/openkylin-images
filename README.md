# 此仓库用于保存Orange Pi开发板的OpenKylin镜像

## 下载OpenKylin镜像

开发板 | 镜像类型 | 下载 |
|:--|:--|:--|
| opi5 | 桌面版本 | [part1](https://github.com/leeboby/openkylin-images/releases/download/orangepi5/opi5_openkylin_aarch64_20230709.tar.gzaa) [part2](https://github.com/leeboby/openkylin-images/releases/download/orangepi5/opi5_openkylin_aarch64_20230709.tar.gzab)|  
```
由于OpenKylin桌面版的镜像压缩后的大小超过了2GB，而github无法上传超过2GB大小的文件，所以将镜像分成了两部分:part1和part2
下载完镜像的part1和part2后可以使用cat命令将它们合并成最终的完整镜像压缩文件，如opi5的合并命令如下所示：

cat opi5_openkylin_aarch64_20230709.tar.gza* > opi5_openkylin_aarch64_20230709.tar.gz
```

## 登录账号和密码


---
![OpenKylin桌面壁纸](https://github.com/leeboby/openkylin-images/blob/main/pictures/desktop.png)
