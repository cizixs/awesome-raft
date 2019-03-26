# awesome-raft

A curated resources of raft consensus algorithm and its friends.

**NOTE**: Contributions are welcome, just create a pull request!

## Raft 

### Algoritm

- The Paper: [Raft: In Search of an Understandable Consensus Algorithm.](https://ramcloud.stanford.edu/wiki/download/attachments/11370504/raft.pdf)
- A nice illustration of raft: [Raft
Understandable Distributed Consensus](http://thesecretlivesofdata.com/raft/)

### Implementations

Due to its simplicity, raft is widely implemented in different lanaguages and softwares, here is some of them:

- [etcd/raft](https://github.com/coreos/etcd): golang implentation used inside etcd 
- [hashicorp/raft](https://github.com/hashicorp/raft): another golang implementation used among hashicorp applications
- [brpc/braft](https://github.com/brpc/braft): C++ implementation open sourced by Baidu Inc.
- [alipay/sofa-jraft](https://github.com/alipay/sofa-jraft): Java implementation by Alipay Inc.

## Raft Friends

Beside Raft, there are some other consensus algorithms that are frequently discussed.

### Chubby

Chubby is invented by Google, and used as a cornerstone of many distributed softwares.

- [The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://research.google.com/archive/chubby.html)

### Paxos

- [Paxos Made Simple](http://research.microsoft.com/en-us/um/people/lamport/pubs/paxos-simple.pdf)

### Zab

Zab protocal is used by Zookeeper, and is proven to be a solid and practical.

- [Zab: A Simple Totally Ordered Broadcast Protocol](https://www.datadoghq.com/pdf/zab.totally-ordered-broadcast-protocol.2008.pdf)

## References

There are other distributed system, consensus algorithm repo you might be interested:

- [Awesome Consensus](https://github.com/dgryski/awesome-consensus)
