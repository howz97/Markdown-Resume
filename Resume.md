 <center>
     <h1>张豪</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             18111257824
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             zhanghao997@qq.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/howz97">howz97</a>
         </span>
         ·
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="https://www.yuque.com/howz97">语雀</a>
         </span>
     </div>
 </center>

 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 求职意向：后端/分布式存储
 - 编程语言：熟悉Golang，用过C++/Rust

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 学士，华北电力大学(保定)，软件工程 【2016~2020】

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- tap4fun，Golang服务器开发 【2020.7~2021.12】

  - 为《猿族时代》开发了联盟机器人，公告栏系统 等功能
  - 为《战地风暴》开发了突变体玩法，及各种活动，负责线上问题排查修复

- 右脚踝手术。自学分布式存储技术 【2021.12~至今】

## <img src="assets/project-diagram-solid.svg" width="30px"> 个人项目

- **Algorithm** : *https://github.com/howz97/algorithm*

  根据教材[《算法》](https://book.douban.com/subject/19952400/)(Sedgewick著) 实现的Golang算法库。首页可查看详细目录，包括：
  - 排序：快速排序、堆排序、Shell排序、归并排序 等等
  - 查找：二叉树、AVL、红黑树、哈希表
  - 图：Kosaraju,Prim,Kruskal,Dijkstra,Topological,BellmanFord 等等
  - 字符串：string排序、Trie树、子串查找、正则匹配、压缩算法
  - 优先队列：二叉堆、左式堆、二项队列

- **MIT6.824** : *https://gitee.com/howz97/mit6.824*

  MIT分布式系统课程。研读Raft,Zookeeper,ChainReplication,Spanner,GFS,MapReduce,Bitcoin等经典论文。拓展阅读了Etcd的Raft源码
  - lab1：实现简单的MapReduce
  - lab2：实现Raft算法库，包括leader选举、PreVote、日志复制、snapshot
  - lab3：实现基于Raft的高可用KV存储
  - lab4：实现Multi-Raft架构的高可用分片KV存储，并实现高可用的Master负责shard迁移

- **TinyKV** : *https://github.com/howz97/tinykv*

  基于TiKV模型构建分布式KV存储服务。
  
  实现Raft库。包括模块：选举、PreVote、日志复制、日志回收与快照、成员配置变更、leader转让、只读操作优化。
  实现Multi-Raft架构的分片的KV存储，包括一致性哈希算法(range分片)、无阻塞shard迁移、基于MVCC的分布式事务

- **CMU15-445**
  
  实验级关系型数据库，C++实现，GradeScope满分通过：
  - 缓冲区管理。多个BufferPool实例并行，LRU策略
  - 索引使用可扩展哈希
  - 查询执行。tuple的增删查改,join,aggregation,limit,distinct，以pipeline模式执行
  - 并发控制。LockManager支持共享锁/锁升级/互斥锁，wound-wait算法避免死锁

- **日志结构KV存储** : *https://github.com/howz97/kvs*
  
  Rust+Tokio实现的单机kv存储，基于bitcask论文，支持后台线程压缩日志。

- **Timer** : *https://crates.io/crates/time_wheel*
  
  Rust实现的timer，采用多级时间轮结构。

## <img src="assets/tools-solid.svg" width="30px"> 技能

- ★★★ Golang、算法、Raft
- ★★☆ Rust、分布式KV
- ★☆☆ Spanner、Bitcoin