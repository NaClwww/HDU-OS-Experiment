# 🎓 HDU操作系统实验

## 📚 项目概述
本项目包含了杭州电子科技大学操作系统课程的实验内容，主要涵盖了Linux内核模块开发、进程通信、文件系统等多个方面的实践。

## 🧪 实验列表

### 🔧 Lab1 - Linux内核模块开发
- **内核版本信息模块**：实现了一个可以显示系统版本信息的内核模块
- **进程ID查看模块**：开发了用于查看进程信息的内核模块
- **系统重启模块**：实现了一个可以通过内核模块重启系统的功能

### 🔄 Lab3 - 进程通信实验
- **消息队列通信**：实现了基于消息队列的线程间通信
- **共享内存通信**：完成了使用共享内存进行进程间通信的实验
- **管道通信**：实现了基于管道的进程间通信机制
- **Shell命令解释器**：开发了一个简单的命令行解释器

### 📂 Lab5 - 文件系统实验
- **简单文件系统**：实现了一个基本的文件系统，支持文件的创建、读写等操作

## ⚙️ 环境要求
- Linux操作系统（推荐Ubuntu或类似发行版）
- GCC编译器
- Make工具
- Linux内核头文件

## 🚀 编译和运行
每个实验都包含独立的Makefile，可以按照以下步骤进行编译和运行：

1. 进入对应的实验目录
```bash
cd Lab<实验编号>/<具体实验>
```

2. 编译代码
```bash
make
```

3. 运行程序（根据具体实验的说明进行）
- 对于内核模块：使用 `insmod` 和 `rmmod` 命令
- 对于用户程序：直接运行编译后的可执行文件

## ⚠️ 注意事项
- 运行内核模块相关实验时需要root权限
- 在进行实验之前，请确保已安装所需的开发工具和库
- 建议在进行实验时参考各实验目录下的README文件获取详细说明

## 👥 贡献者
- douzza
- Ec3o

## 📄 许可证
本项目采用GPL许可证