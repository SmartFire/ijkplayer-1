# ijkplayer
基于bilibili开源播放器编译好的so包项目，可直接通过lib的方式进行引用。

优化了下control的实现方式,从dialog替换成view的显示隐藏.

## Usage
Add this line to your `build.gradle` file under your module directory. 

```
    compile 'com.github.leifzhang:IjkLib:0.1.3'
```
# 简介
更新了一下ijk的版本号以及升级了一下so包.

正常情况下可以考虑参考以下代码,可以简单的过滤项目的so包.

```
  defaultConfig {
        ndk {
            abiFilters 'armeabi', ' 'x86'
        }
    }
```

升级了ijkplayer的so包以及java代码，同时更好的对lib代码迁移，方便直接关联项目的方式引入。
同时感谢bilibili大神们开源。