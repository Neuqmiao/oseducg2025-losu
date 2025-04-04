## 项目名称
基于洛书（Losu）编程语言与 Web Assembly 的编译与OS演示系统

## 支持单位
东北大学秦皇岛分校、希冀信息类专业教学实践一体化平台 

## 项目描述

+ 洛书（Losu）是一款新兴的轻量级脚本语言，采用 编译器 + 虚拟机 的设计，支持用户态线程、自动内存管理、文件操作等功能。

+ 本项目需要基于 Losu 语言，结合 Web Assembly 技术，开发一个编程教学环境，模拟并演示程序在OS中的执行过程，包括：
    - 源代码编写（使用 Losu 编写源文件）
    - 编译功能演示（生成 Losu 字节码文件）
    - OS 功能演示（运行 Losu 字节码，演示内存管理、文件操作、线程调度等过程）


## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 参赛要求

+ 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
+ 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖；
+ 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求；

## 项目导师

+ 方淼
    - github github.com/Neuqmiao
    - Email  fangmiao@neuq.edu.cn

## 难度
中

# License
GPL V3.0.

## 预期目标

+ 初级目标：实现在 Web Assembly 环境中运行 Losu 编译器与虚拟机，并实现基本的用户线程、内存管理、文件操作等功能。

+ 中级目标：
    - 完善系统功能，如：
        - 线程调度：实现线程调度器，可采用任意常用的调度算法。
        - 内存管理：实现内存分配器，可采用任意常用的内存管理算法。
        - 文件操作：实现文件读写、目录创建、文件删除等功能，支持将工作目录导出为压缩包。
    - 实现图形化界面，实时显示系统状态。

+ 高级目标：
    - 实现代码编辑器，可选择 Web Playground、Vscode 插件等形式。
    - 进一步丰富系统功能，如：
        - 线程调度：实现多种调度算法，支持用户选择所需的调度算法。
        - 内存管理：实现多种内存管理算法，支持用户选择所需的内存管理算法。
    - 完成项目打包与部署，编写说明文档。

+ 选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

## 参考资源
+ [Emscripten](https://emscripten.org/docs/compiling/index.html)，是一个完整的编译工具链，用于将代码编译为 WebAssembly，它使用 LLVM，并特别注重速度、大小和 Web 平台的特性。
+ [The BGET Memory Allocator](https://www.fourmilab.ch/bget/)
+ 洛书编译器与虚拟机源代码参考：[2023版本](https://gitcode.com/losu-lang/Losu-lang-sdk/tree/pre)、[2024版本](https://gitcode.com/losu-lang/Losu-lang-sdk/tree/ospp-2024-hdq)

## 备注
+ 信息交流群 QQ：675772374 
