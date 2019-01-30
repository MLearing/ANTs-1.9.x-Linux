# Nipype-N4BiasFieldCorrection-Bin
nipype调用N4BiasFieldCorrection函数时需要安装ANTs的库文件，nipype只是实现了N4BiasFieldCorrection函数的接口，并没有实现函数的功能，所以如果要使用该函数需要编译ANTs的源码，或者直接使用这个编译好的bin文件，只需要把该二进制文件配置好环境变量即可。

## 环境配置
最简单的方法就是直接放到/usr/bin/文件夹下面便可使用，因为系统环境变量已经在环境变量中

## 源码编译安装
参考：
