# proj-linux-cpu-cpp

## linux-cpu-cpp
Linux内核CPU管理功能对象化初步实现

### 【项目描述】
Linux内核对CPU管理有一系列的接口，例如CPU的在线使能、在线禁用等。如果把CPU作为一个对象进行管理，则可以清晰地描述CPU与管理者的交互，也能方便后继对相关功能的修改。C++语言提供了面向对象的语言层面支持，使对象的管理更为清晰。本项目拟利用C++语言对Linux的CPU管理机制进行对象化改造。

### 【所属赛道】
2022全国大学生操作系统比赛的“OS功能设计”赛道

### 【参赛要求】
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

### 【项目导师】
刘志立
- github https://github.com/liuzhili-ya
- email zhili.liu@ucas.com.cn

### 【难度】
中等

### 【License】
MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)  

## 【预期目标】
- 完成Linux内核部分CPU管理功能的C++改造
- 系统能平稳运行

### 【参考资源】
- C++语言相关书籍
- Linux内核CPU热插拔资源(
https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/core-api/cpu_hotplug.rst)
