例子索引
=======

## chapter2

- (msreader)[1]
- (mspoller)[2]
- (rrclient)[3]
- (rrworker)[4]
- (rrbroker)[5]
- (msgqueue)[6]: zmq 内置 proxy 函数
- (wuproxy)[7]: transport bridging
- (taskwork2)[8]: parallel task worker with killing signaling
- (tasksink2)[9]: parallel task sink with killing signaling

### handling interrupt signals

- (interrupt)[10]: 处理中断信号

### detecting memory leaks
### multithreading with zeromq

- (mtserver)[11] helloworld 多线程版本

### signaling between threads (pair sockets)

- (mtrelay)[12] 多线程 relay

### node cordination

- (syncpub)[13] req-rep 同步的 subscriber
- (syncsub)[14] 对应的 publisher

### zero-copy

### pub-sub message envelopes 信封

- (psenvpub)[15] pub 发布多帧，[envelope, content]
- (psenvsub)[16] [addr, contents] = sub.recv_multipart()

### high-water marks

### missing message problem solver

## chapter3

### the request-reply mechanisms

#### the simple reply envelope

#### the extended reply envelope

#### what's this good for?

#### recap of request-reply sockets

### request-reply combinations

### exploring router sockets

#### identities and addresses

- (identity)[17] 用 setsockopt/zmq.IDENTITY 设置 identity

#### router error handling

### the load balancing pattern

#### ROUTER broker and REQ workers

- (rtreq)[18] ROUTER broker talking to a set of REQ

#### ROUTER broker and DEALER workers

- (rtdealer)[19] ROUTER broker talking to a set of DEALER

#### a load balancing message broker

- (lbbroker)[20] load balancing broker

### a high-level api for zmq

#### features of higher-level api

#### the czmq high-level api

- (lbbroker2)[21]
- (lbbroker3)[22]

### the asynchronous client/server pattern

- (asyncsrv)[23]

### worked example: inter-broker routing

- (peering1)[24]
- (peering2)[25]
- (perring3)[26]