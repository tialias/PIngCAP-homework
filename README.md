# PingCAP-homework

## 题目描述
题目：为 TiDB 的 range 分区表设计测试用例，用例不需要详细的执行步骤，但需要尽可能覆盖全面并且有输入输出，参考：https://docs.pingcap.com/zh/tidb/stable/partitioned-table#range-%E5%88%86%E5%8C%BA


## 测试功能分析（range分区表）

#### 规则
- 必须是连续的
- 不能重复
- VALUES LESS THAN定义
- 当前元素不在分区范围内，报错
- 对NULL的处理
#### 管理分区表单
- 创建分区表
- 删除分区
- 清空分区
- 添加分区
#### 分区的约束和限制
- 分区表的每个唯⼀键，必须包含分区表达式中⽤到的所有列。
- 函数的分区限制
#### 分区裁剪功能
- 裁剪生效
#### 分区表
- 新增数据
- 查询数据
- 删除数据
- 修改数据



###  [测试用例](https://github.com/tialias/PingCAP-homework/blob/master/%E6%B5%8B%E8%AF%95%E7%94%A8%E4%BE%8B.md)
    
