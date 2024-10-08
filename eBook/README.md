# 目录

* 前言

## 第一部分：学习 Go 语言

* 第 1 章：Go 语言的起源，发展与普及
  * 1.1 起源与发展
  * 1.2 语言的主要特性与发展的环境和影响因素
* 第 2 章：安装与运行环境
  * 2.1 平台与架构
  * 2.2 Go 环境变量
  * 2.3 在 Linux 上安装 Go
  * 2.4 在 Mac OS X 上安装 Go
  * 2.5 在 Windows 上安装 Go
  * 2.6 安装目录清单
  * 2.7 Go 运行时 (runtime)
  * 2.8 Go 解释器
* 第 3 章：编辑器、集成开发环境与其它工具
  * 3.1 Go 开发环境的基本要求
  * 3.2 编辑器和集成开发环境
  * 3.3 调试器
  * 3.4 构建并运行 Go 程序
  * 3.5 格式化代码
  * 3.6 生成代码文档
  * 3.7 其它工具
  * 3.8 Go 性能说明
  * 3.9 与其它语言进行交互

## 第二部分：语言的核心结构与技术

* 第 4 章：基本结构和基本数据类型
  * 4.1 文件名、关键字与标识符
  * 4.2 Go 程序的基本结构和要素
  * 4.3 常量
  * 4.4 变量
  * 4.5 基本类型和运算符
  * 4.6 字符串
  * 4.7 strings 和 strconv 包
  * 4.8 时间和日期
  * 4.9 指针
* 第 5 章：控制结构
  * 5.1 if-else 结构
  * 5.2 测试多返回值函数的错误
  * 5.3 switch 结构
  * 5.4 for 结构
  * 5.5 Break 与 continue
  * 5.6 标签与 goto
* 第 6 章：函数 (function)
  * 6.1 介绍
  * 6.2 函数参数与返回值
  * 6.3 传递变长参数
  * 6.4 defer 和追踪
  * 6.5 内置函数
  * 6.6 递归函数
  * 6.7 将函数作为参数
  * 6.8 闭包
  * 6.9 应用闭包：将函数作为返回值
  * 6.10 使用闭包调试
  * 6.11 计算函数执行时间
  * 6.12 通过内存缓存来提升性能
* 第 7 章：数组与切片
  * 7.1 声明和初始化
  * 7.2 切片
  * 7.3 For-range 结构
  * 7.4 切片重组 (reslice)
  * 7.5 切片的复制与追加
  * 7.6 字符串、数组和切片的应用
* 第 8 章：Map
  * 8.1 声明、初始化和 make
  * 8.2 测试键值对是否存在及删除元素
  * 8.3 for-range 的配套用法
  * 8.4 map 类型的切片
  * 8.5 map 的排序
  * 8.6 将 map 的键值对调
* 第 9 章：包 (package)
  * 9.1 标准库概述
  * 9.2 regexp 包
  * 9.3 锁和 sync 包
  * 9.4 精密计算和 big 包
  * 9.5 自定义包和可见性
  * 9.6 为自定义包使用 godoc
  * 9.7 使用 go install 安装自定义包
  * 9.8 自定义包的目录结构、go install 和 go test
  * 9.9 通过 Git 打包和安装
  * 9.10 Go 的外部包和项目
  * 9.11 在 Go 程序中使用外部库
* 第 10 章：结构 (struct) 与方法 (method)
  * 10.1 结构体定义
  * 10.2 使用工厂方法创建结构体实例
  * 10.3 使用自定义包中的结构体
  * 10.4 带标签的结构体
  * 10.5 匿名字段和内嵌结构体
  * 10.6 方法
  * 10.7 类型的 String() 方法和格式化描述符
  * 10.8 垃圾回收和 SetFinalizer
* 第 11 章：接口 (interface) 与反射 (reflection)
  * 11.1 接口是什么
  * 11.2 接口嵌套接口
  * 11.3 类型断言：如何检测和转换接口变量的类型
  * 11.4 类型判断：type-switch
  * 11.5 测试一个值是否实现了某个接口
  * 11.6 使用方法集与接口
  * 11.7 第一个例子：使用 Sorter 接口排序
  * 11.8 第二个例子：读和写
  * 11.9 空接口
  * 11.10 反射包
  * 11.11 Printf 和反射
  * 11.12 接口与动态类型
  * 11.13 总结：Go 中的面向对象
  * 11.14 结构体、集合和高阶函数

## 第三部分：Go 高级编程

* 第 12 章：读写数据
  * 12.1 读取用户的输入
  * 12.2 文件读写
  * 12.3 文件拷贝
  * 12.4 从命令行读取参数
  * 12.5 用 buffer 读取文件
  * 12.6 用切片读写文件
  * 12.7 用 defer 关闭文件
  * 12.8 使用接口的实际例子：fmt.Fprintf
  * 12.9 JSON 数据格式
  * 12.10 XML 数据格式
  * 12.11 用 Gob 传输数据
  * 12.12 Go 中的密码学
* 第 13 章：错误处理与测试
  * 13.1 错误处理
  * 13.2 运行时异常和 panic
  * 13.3 从 panic 中恢复 (recover)
  * 13.4 自定义包中的错误处理和 panicking
  * 13.5 一种用闭包处理错误的模式
  * 13.6 启动外部命令和程序
  * 13.7 Go 中的单元测试和基准测试
  * 13.8 测试的具体例子
  * 13.9 用（测试数据）表驱动测试
  * 13.10 性能调试：分析并优化 Go 程序
* 第 14 章：协程 (goroutine) 与通道 (channel)
  * 14.1 并发、并行和协程
  * 14.2 协程间的信道
  * 14.3 协程的同步：关闭通道-测试阻塞的通道
  * 14.4 使用 select 切换协程
  * 14.5 通道、超时和计时器 (Ticker)
  * 14.6 协程和恢复 (recover)
  * 14.7 新旧模型对比：任务和worker
  * 14.8 惰性生成器的实现
  * 14.9 实现 Futures 模式
  * 14.10 复用
  * 14.11 限制同时处理的请求数
  * 14.12 链式协程
  * 14.13 在多核心上并行计算
  * 14.14 并行化大量数据的计算
  * 14.15 漏桶算法
  * 14.16 对Go协程进行基准测试
  * 14.17 使用通道并发访问对象
* 第 15 章：网络、模板与网页应用
  * 15.1 tcp 服务器
  * 15.2 一个简单的 web 服务器
  * 15.3 访问并读取页面数据
  * 15.4 写一个简单的网页应用
  * 15.5 确保网页应用健壮
  * 15.6 用模板编写网页应用
  * 15.7 探索 template 包
  * 15.8 精巧的多功能网页服务器
  * 15.9 用 rpc 实现远程过程调用
  * 15.10 基于网络的通道 netchan
  * 15.11 与 websocket 通信
  * 15.12 用 smtp 发送邮件

## 第四部分：实际应用

* 第 16 章：常见的陷阱与错误
  * 16.1 误用短声明导致变量覆盖
  * 16.2 误用字符串
  * 16.3 发生错误时使用 defer 关闭一个文件
  * 16.4 何时使用 new() 和 make()
  * 16.5 不需要将一个指向切片的指针传递给函数
  * 16.6 使用指针指向接口类型
  * 16.7 使用值类型时误用指针
  * 16.8 误用协程和通道
  * 16.9 闭包和协程的使用
  * 16.10 糟糕的错误处理
* 第 17 章：模式
  * 17.1 逗号 ok 模式
  * 17.2 defer 模式
  * 17.3 可见性模式
  * 17.4 运算符模式和接口
* 第 18 章：出于性能考虑的实用代码片段
  * 18.1 字符串
  * 18.2 数组和切片
  * 18.3 映射
  * 18.4 结构体
  * 18.5 接口
  * 18.6 函数
  * 18.7 文件
  * 18.8 协程 (goroutine) 与通道 (channel)
  * 18.9 网络和网页应用
  * 18.10 其他
  * 18.11 出于性能考虑的最佳实践和建议
* 第 19 章：构建一个完整的应用程序
  * 19.1 简介
  * 19.2 短网址项目简介
  * 19.3 数据结构
  * 19.4 用户界面：web 服务端
  * 19.5 持久化存储：gob
  * 19.6 用协程优化性能
  * 19.7 以 json 格式存储
  * 19.8 多服务器处理架构
  * 19.9 使用代理缓存
  * 19.10 总结和增强
* 第 20 章：Go 语言在 Google App Engine 的使用
  * 20.1 什么是 Google App Engine？
  * 20.2 云上的 Go
  * 20.3 安装 Go App Engine SDK：为 Go 部署的开发环境
  * 20.4 建造你自己的 Hello world 应用
  * 20.5 使用用户服务和探索其 API
  * 20.6 处理窗口
  * 20.7 使用数据存储
  * 20.8 上传到云端
* 第 21 章：真实世界中 Go 的使用
  * 21.1 Heroku：一个使用 Go 的高度可用一致数据存储
  * 21.2 MROffice：一个使用 Go 的呼叫中心网络电话 (VOIP) 系统
  * 21.3 Atlassian：一个虚拟机群管理系统
  * 21.4 Camilistore：一个可寻址内容存储系统
  * 21.5 Go 语言的其他应用

## 附录

* A 代码引用
* B 有趣的 Go 引用
* C 代码示例列表
* D 书中的包引用
* E 书中的工具引用
* F 常见问题解答
* G 习题答案
* H 参考文献
