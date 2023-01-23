# FTXUI

This project builds and defines the build2 package for the [FTXUI](https://github.com/ArthurSonzogni/FTXUI) library.

The packaging code is licensed under the MIT License, the upstream artifacts are licensed under the terms and conditions of FTXUI.

## Usage

You can simply add this package as dependency to your project by specifying it in your `manifest`:

```
depends: libftxui ^3.0.0
```

Then just pick the targets that you need:

```
import ftxui_libs  = libftxui%lib{ftxui-screen}
import ftxui_libs += libftxui%lib{ftxui-dom}
import ftxui_libs += libftxui%lib{ftxui-component}
```
