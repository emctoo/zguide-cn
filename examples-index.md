例子索引
=======

### chapter2

- (msreader)[1]
- (mspoller)[2]
- (rrclient)[3]
- (rrworker)[4]
- (rrbroker)[5]
- (msgqueue)[6]: zmq 内置 proxy 函数
- (wuproxy)[7]: transport bridging
- (taskwork2)[8]: parallel task worker with killing signaling
- (tasksink2)[9]: parallel task sink with killing signaling

#### handling interrupt signals

- (interrupt)[10]: 处理中断信号

#### detecting memory leaks
#### multithreading with zeromq

- (mtserver)[11] helloworld 多线程版本

#### signaling between threads (pair sockets)

- (mtrelay)[12] 多线程 relay

#### node cordination

- (syncpub)[13] req-rep 同步的 subscriber
- (syncsub)[14] 对应的 publisher

#### zero-copy

#### pub-sub message envelopes 信封

- (psenvpub)[15] pub 发布多帧，[envelope, content]
- (psenvsub)[16] [addr, contents] = sub.recv_multipart()

#### high-water marks

#### missing message problem solver

 [1] msreader.py
 [2] mspoller.py
 [3] rrclient.py
 [4] rrworker.py
 [5] rrbroker.py
 [6] msgqueue.py