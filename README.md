# 目录
* [线程模型](docs/thread_model.md)
  * [client](docs/client.md)
  * [server](docs/server.md)
* 网络I/O
  * [protobuf编程模式](docs/io_protobuf.md)
  * [多线程向同一TCP连接写入数据](docs/io_write.md)
  * [从TCP连接读取数据](docs/io_read.md)
* Client端执行流程
  * [无异常状态下的一次完整RPC请求过程](docs/client_rpc_normal.md)
  * 重试策略
  * Backup Request
  * [同一RPC过程中各个bthread间的同步](docs/client_bthread_sync.md)
* Server端执行流程
  * 处理一次请求的完整过程
  * 服务限流
  * 防雪崩
* bthread 
  * 调度算法
  * [同步策略](docs/bthread_sync_strategy.md)
  * [线程futex同步](docs/futex.md)
* 性能监控
* 基础库
  * 对象池
  * 定时器
  * 计数器
