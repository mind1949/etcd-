# etcd 中 raft 协议的设计与实现

## 解决以下问题

- [ ] etcd/raft
  - [ ] etcd/raft 如何实现 [raft-extended](https://raft.github.io/raft.pdf)
    - [ ] 日志复制
    - [ ] 领导选举
    - [ ] 成员变更
    - [ ] leader transfer
    - [ ] 日志压缩
  - [ ] 作为工业级实现, etcd/raft 有哪些优化
    - [ ] 目的是什么?
    - [ ] 原理是什么?
    - [ ] 如何自己实现?
  - [ ] 整理评价 etcd/raft 的设计与实现
    - [ ] 宏观上 etcd/raft 是如何设计实现 raft 协议的?
    - [ ] 让它成为工业级实现的点是什么?
    - [ ] 有哪些缺点?
    - [ ] 怎样做更好?

# 日志复制

TODO:
