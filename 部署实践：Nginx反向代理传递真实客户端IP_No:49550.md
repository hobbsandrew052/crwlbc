最新前沿技术资讯

一、入门教程｜Getting Started
原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.rlxsjj.asia/arts/737115.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.rlxsjj.asia/arts/642444.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.rlxsjj.asia/arts/374265.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.rlxsjj.asia/arts/423224.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.rlxsjj.asia/arts/822007.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.rlxsjj.asia/arts/051313.Doc

原标题：golang redis 位图用户签到统计
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.rlxsjj.asia/arts/960484.Doc

原标题：数据库事务 ACID 原理讲解
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.rlxsjj.asia/arts/974924.Doc

原标题：Security：服务器最小权限账号运维实践
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.rlxsjj.asia/arts/716121.Doc

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.rlxsjj.asia/arts/075274.Doc

原标题：golang 消息死信处理业务逻辑
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.rlxsjj.asia/arts/301610.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.rlxsjj.asia/arts/815390.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.rlxsjj.asia/arts/046050.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.rlxsjj.asia/arts/713905.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.rlxsjj.asia/arts/492879.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.rlxsjj.asia/arts/962867.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.rlxsjj.asia/arts/635398.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.rlxsjj.asia/arts/338660.Doc

原标题：golang k8s 资源请求限制配置
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.rlxsjj.asia/arts/728763.Doc

原标题：文件句柄上限调整上传随机失败
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.rlxsjj.asia/arts/253277.Doc

原标题：Git 代码冲突正确处理方式
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.rlxsjj.asia/arts/000099.Doc

原标题：Shell 脚本自动化命令编写
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.rlxsjj.asia/arts/204957.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.rlxsjj.asia/arts/953243.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.rlxsjj.asia/arts/256729.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.rlxsjj.asia/arts/530028.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.rlxsjj.asia/arts/578734.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.rlxsjj.asia/arts/428165.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.rlxsjj.asia/arts/530146.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.rlxsjj.asia/arts/189659.Doc

原标题：golang redis 锁超时业务处理
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.rlxsjj.asia/arts/041002.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.rlxsjj.asia/arts/011094.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.rlxsjj.asia/arts/904009.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.rlxsjj.asia/arts/392241.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.rlxsjj.asia/arts/788339.Doc

原标题：golang validator 自定义校验规则
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.rlxsjj.asia/arts/485431.Doc

原标题：文件监控服务自动重启开发
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.rlxsjj.asia/arts/123938.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.rlxsjj.asia/arts/937602.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.rlxsjj.asia/arts/600553.Doc

原标题：golang aes 对称加密解密示例
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.rlxsjj.asia/arts/862002.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.rlxsjj.asia/arts/796323.Doc


二、踩坑排错｜Troubleshooting
原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.rlxsjj.asia/arts/275951.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.rlxsjj.asia/arts/393689.Doc

原标题：数据库事务 ACID 原理讲解
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.rlxsjj.asia/arts/747961.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.rlxsjj.asia/arts/186967.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.rlxsjj.asia/arts/521214.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.rlxsjj.asia/arts/991632.Doc

原标题：golang 布隆过滤器实现去重
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.rlxsjj.asia/arts/667813.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.rlxsjj.asia/arts/092839.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.rlxsjj.asia/arts/373127.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.rlxsjj.asia/arts/599771.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.rlxsjj.asia/arts/392456.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.rlxsjj.asia/arts/447440.Doc

原标题：依赖版本冲突兼容修复方案
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.rlxsjj.asia/arts/378345.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.rlxsjj.asia/arts/469471.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.rlxsjj.asia/arts/850910.Doc

原标题：golang redis 连接池参数最佳值
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.rlxsjj.asia/arts/406145.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.rlxsjj.asia/arts/601687.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.rlxsjj.asia/arts/562226.Doc

原标题：文件读写与异常捕获代码示例
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.rlxsjj.asia/arts/929888.Doc

原标题：golang 系统设计多级缓存架构落地
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.rlxsjj.asia/arts/134624.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.rlxsjj.asia/arts/049176.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.rlxsjj.asia/arts/678772.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.rlxsjj.asia/arts/454005.Doc

原标题：实践：数据库回滚点业务调试实践
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.rlxsjj.asia/arts/469148.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.rlxsjj.asia/arts/078479.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.rlxsjj.asia/arts/601784.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.rlxsjj.asia/arts/808991.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.rlxsjj.asia/arts/318346.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.rlxsjj.asia/arts/485066.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.rlxsjj.asia/arts/881369.Doc

原标题：golang redis 集群 hash 槽讲解
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.rlxsjj.asia/arts/256935.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.rlxsjj.asia/arts/237608.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.rlxsjj.asia/arts/167989.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.rlxsjj.asia/arts/600952.Doc

原标题：GraphQL 接口查询优化实操
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.rlxsjj.asia/arts/012144.Doc

原标题：定时任务重复执行分布式锁
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.rlxsjj.asia/arts/881163.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.rlxsjj.asia/arts/423687.Doc

原标题：正则表达式文本处理实战案例
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.rlxsjj.asia/arts/030795.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.rlxsjj.asia/arts/081833.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.rlxsjj.asia/arts/296614.Doc

三、实战开发｜Practice
原标题：golang 单元测试 mock http 请求
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.rlxsjj.asia/arts/186281.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.rlxsjj.asia/arts/129625.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.rlxsjj.asia/arts/641809.Doc

原标题：golang minio 分片上传断点续传
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.rlxsjj.asia/arts/904233.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.rlxsjj.asia/arts/827367.Doc

原标题：服务器时钟同步任务错乱修复
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.rlxsjj.asia/arts/590079.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.rlxsjj.asia/arts/234089.Doc

原标题：开发环境变量配置全平台教程
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.rlxsjj.asia/arts/799327.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.rlxsjj.asia/arts/153709.Doc

原标题：nodejs 全局异常捕获进程防护
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.rlxsjj.asia/arts/151712.Doc

原标题：golang viper 配置热更新实操
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.rlxsjj.asia/arts/728497.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.rlxsjj.asia/arts/195744.Doc

原标题：多套环境灵活切换配置方案
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.rlxsjj.asia/arts/295239.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.rlxsjj.asia/arts/945027.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.rlxsjj.asia/arts/266983.Doc

原标题：后端登录鉴权模块完整开发
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.rlxsjj.asia/arts/807998.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.rlxsjj.asia/arts/521628.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.rlxsjj.asia/arts/201075.Doc

原标题：golang docker 运行 etcd 本地测试
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.rlxsjj.asia/arts/860654.Doc

原标题：golang 系统设计会话共享多实例部署
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.rlxsjj.asia/arts/921082.Doc

原标题：golang mysql 主从同步延迟兼容
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.rlxsjj.asia/arts/241673.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.rlxsjj.asia/arts/722476.Doc

原标题：golang http 代理客户端配置
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.rlxsjj.asia/arts/348366.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.rlxsjj.asia/arts/107635.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.rlxsjj.asia/arts/718300.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.rlxsjj.asia/arts/683562.Doc

原标题：golang redis 限流几种实现方案
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.rlxsjj.asia/arts/861369.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.rlxsjj.asia/arts/187699.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.rlxsjj.asia/arts/890148.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.rlxsjj.asia/arts/780263.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.rlxsjj.asia/arts/594296.Doc

原标题：Cookie Session 会话状态管理
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.rlxsjj.asia/arts/450977.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.rlxsjj.asia/arts/109841.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.rlxsjj.asia/arts/317447.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.rlxsjj.asia/arts/597326.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.rlxsjj.asia/arts/335716.Doc

原标题：nodejs 集群模式多核利用实现
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.rlxsjj.asia/arts/468607.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.rlxsjj.asia/arts/807909.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.rlxsjj.asia/arts/023934.Doc

原标题：磁盘占满服务不可用清理方案
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.rlxsjj.asia/arts/463454.Doc

四、架构设计｜Architecture
原标题：零基础理解缓存基础原理与简单使用
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.rlxsjj.asia/arts/038864.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.rlxsjj.asia/arts/115542.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.rlxsjj.asia/arts/810439.Doc

原标题：全平台系统环境变量配置
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.rlxsjj.asia/arts/591937.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.rlxsjj.asia/arts/979637.Doc

原标题：golang redis 缓存预热实现思路
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.rlxsjj.asia/arts/564414.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.rlxsjj.asia/arts/701838.Doc

原标题：文件监控服务自动重启开发
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.rlxsjj.asia/arts/207691.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.rlxsjj.asia/arts/255948.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.rlxsjj.asia/arts/898297.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.rlxsjj.asia/arts/955212.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.rlxsjj.asia/arts/678475.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.rlxsjj.asia/arts/424649.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.rlxsjj.asia/arts/803394.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.rlxsjj.asia/arts/807932.Doc

原标题：前端图片懒加载性能优化
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.rlxsjj.asia/arts/305920.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.rlxsjj.asia/arts/425386.Doc

原标题：布隆过滤器数据高效去重实现
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.rlxsjj.asia/arts/453306.Doc

?
