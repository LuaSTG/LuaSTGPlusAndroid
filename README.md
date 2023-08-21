# LuaSTGPlusAndroid

该仓库为[LuaSTGPlus](https://github.com/9chu/LuaSTGPlus)的安卓版本。

建议使用`IntelliJ IDEA`进行开发。

**Working in progress**

## 工程结构

- `app/jni`：以`submodule`引入`LuaSTGPlus`仓库代码，并通过`NDK`进行编译
- `app/src/main`
  - `assets`：游戏资源目录，请在打包前将资源文件存放此处
  - `java`：Java层实现，基于`SDL2`代码构建

## 编译

由于`luajit`限定`gcc/clang`，需要在`Linux`环境编译。
