## bulbasaur调度模块设计 ##

### 需求和目的 ###

提供可靠的异步、定时、重复和分布式的调用机制。

- 异步：流程的异步执行，部分节点的异步执行
- 定时：定时发起/完成节点，定时执行回调
- 重复：对失败节点的可配置的重试
- 分布式：跨业务组的流程执行

###