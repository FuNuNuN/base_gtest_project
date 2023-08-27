# base_gtest_project
a simple and basic gtest project

参考：[如何fork自己的github库？](https://cloud.tencent.com/developer/article/1556687) 将此仓作为其他工程的模板
# Env
```shell
# init Gtest
git submodule update --init --recursive
```
# Usage
```shell
# project root path
mkdir build && cd build
cmake ../
make -j
./test/alg_ut
```