# rust-learn
学习rust的一些笔记

### 认识 cargo 命令
`cargo --version` 验证 cargo 是否正确安装

### Hello world！
`cargo new` 创建一个文件夹名字跟工程名称一致，然后初始化一个工程。

`cargo init` 在已存在的目录下初始化一个rust工程。

`cargo new hello_world` 创建一个叫hello_world的工程

`cargo new` 时增加 `--vcs` flag 来确定使用 vcs 何种 vcs 或者不是用 vcs ，默认使用 git 。


### rust工程的结构

src 目录
- main.rs   文件

Cargo.lock  文件

Cargo.toml  文件 (Tom`s Obvious,Minimal Language) 
