# Glass（二代）软件开发文档

[![Build Status](https://travis-ci.org/RokidGlass/glass2-docs.svg?branch=master)](https://travis-ci.org/github/RokidGlass/glass2-docs)

## 介绍
-   本文档面向Rokid Glass的开发者，介绍了开发者如何在Rokid Glass上开发应用。
-   本文档包含了系统配置方法，Rokid Glass SDK使用文档，眼镜管家公版App的介绍。  

## 如何在Glass上开发App？
-   开发者可以基于Rokid提供的SDK开发眼镜端App，或者用已有的Android App做眼镜适配。
-   眼镜适配方法（与Android手机上App的开发区别）：
    -   Touch screen -> Touch pad：部分类型的控件需要自定义焦点控制。
    -   有preview -> 无preview：真实世界不需要preview（具体可参考UI SDK）。
    -   相机映射alignment：相机世界需要映射到真实世界（具体可参考UI SDK）。
    -   Glass风格的UI：参考UI设计规范和UI SDK。
    -   如果需要使用系统AR投屏功能, 建议使用Android Camera2.0开发应用。

## 下载若琪慧眼·手机公版App
最新版本手机App下载地址： [若琪慧眼·手机公版App](3-app/1-android/download.md)   
如果要体验眼镜最新功能，请[升级眼镜系统到最新版本](0-faq/#二、ota升级).

## [FAQ](0-faq/index.md)
