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

## OpenKylin系统默认密码

OpenKylin系统是没有提供默认密码的，登录桌面后自己设置一个密码就行了，不要再来问默认密码是多少了。

为什么不提供默认密码，因为OpenKylin官方做的系统就是这样的。

---
![OpenKylin桌面壁纸](https://github.com/leeboby/openkylin-images/blob/main/pictures/desktop.png)
