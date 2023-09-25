# tbb
learn tbb 

源码下载：
https://github.com/oneapi-src/oneTBB/releases/tag/v2020.3

源码编译：

windows编译：

  进入TBB文件夹，执行命令mingw32-make compiler=gcc arch=intel64
  mingw32-make compiler=gcc arch=intel64 runtime=mingw extra_inc=big_iron.inc tbb
  
Linux编译：

  make CC=aarch64-linux-gnu-gcc CXX=aarch64-linux-gnu-g++
