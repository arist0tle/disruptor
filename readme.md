# 这个系统能做什么？
- 这个一个研究学习高性能套接字的工程
- 工程初始状态不需要任何依赖
- 原始的disruptor工程是由一家欧洲金融公司LAMX开发的内部系统，使用gradle管理依赖和构建
- 我的计划是阅读这个项目的每一行代码，并理解它的设计初衷
- 这是一个长期的开源项目，计划持续很久

# 开发计划是什么？
- 计划是用disruptor构建一个高并发服务

# 支持的协议有哪些？
- 协议
    * 支持tcp和http，主要是tcp

# 模块的分工如何？
- 模块划分：
    * disruptor-common    公共依赖模块
    * disruptor-core      后端核心模块
    * disruptor-server    服务层模块  这里提供套接字访问
    * disruptor-api       提供外部接口，含tcp和http
    * disruptor-example   测试用例集合，由于工程可能会比较庞大，测试用例集中到一个模块

# 如何构建？


# disruptor的原理是什么？


# RingBuffer的奥秘在哪里？


# 线程之间如何协调？


# 是否支持分布式？


# 缓存机制？


# 其他问题


xxxxx
