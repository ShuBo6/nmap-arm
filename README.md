本来看了下官网没有arm版本的nmap包，萌生想法想自己用源代码编一个。

但是突然脑中一闪，好像可以先看下openEuler的yum mirror站有没有nmap
于是试了下

```
 yum install --downloadonly --downloaddir=. nmap
```
显然，镜像站有。例如：
```
https://mirrors.aliyun.com/openeuler/openEuler-22.03-LTS-SP3/OS/aarch64/Packages/nmap-7.92-7.oe2203sp3.aarch64.rpm
https://repo.huaweicloud.com/openeuler/openEuler-22.03-LTS-SP3/OS/aarch64/Packages/nmap-7.92-7.oe2203sp3.aarch64.rpm
```
所以先不编了。
