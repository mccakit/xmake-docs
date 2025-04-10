# Introduction

What is Xmake?

1. Xmake is a cross-platform build utility based on the Lua scripting language.
2. Xmake is very lightweight and has no dependencies outside of the standard library.
3. Uses the `xmake.lua` file to maintain project builds with a simple and readable syntax.

Xmake can be used to directly build source code (like with Make or Ninja), or it can generate project source files like CMake or Meson. It also has a *built-in* package management system to help users integrate C/C++ dependencies.

```
Xmake = Build backend + Project Generator + Package Manager + [Remote|Distributed] Build + Cache
```

Although less precise, one can still understand Xmake in the following way:

```
Xmake ≈ Make/Ninja + CMake/Meson + Vcpkg/Conan + distcc + ccache/sccache
```

If you want to know more, please refer to: the [Documentation](https://xmake.io/#/getting_started), [GitHub](https://github.com/xmake-io/xmake) or [Gitee](https://gitee.com/tboox/xmake). You are also welcome to join our [community](https://xmake.io/#/about/contact).

The official Xmake repository can be found at [xmake-io/xmake-repo](https://github.com/xmake-io/xmake-repo).

# 
