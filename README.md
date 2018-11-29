# M11：[并发处理](https://github.com/OS-Q/M11) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属设备体系：[Q4](https://github.com/OS-Q/Q4)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M11/wiki) 

M11并发处理节点，启用更多备用资源，通过增加数量分流实现性能扩展和补足

### [共用资源](https://github.com/OS-Q/M11/wiki/src) 


---

边缘设备命名规则：体系 Q[1,4] > 节点 M[1,12] > 平台 W[1,52] > 设备 D[1,365]。

## [包含平台](https://github.com/OS-Q/M11/wiki/index) 

#### W44：[多级缓冲](https://github.com/OS-Q/W44)

增加多级缓冲，通过时间均摊性能(时间成本)

#### W45：[通道增强](https://github.com/OS-Q/W45)

增强相应通道，提高并发通信能力(通信成本)

#### W46：[流水处理](https://github.com/OS-Q/W46)

优化处理效率，高效率的流水组合(效能成本)

#### W47：[任务分割](https://github.com/OS-Q/W47)

分割处理内容，降低处理任务规模(数量成本)

#### W48：[规模扩展](https://github.com/OS-Q/W48)

优化群组结构，通过数量解决短板(空间成本)


## [同级节点](https://github.com/OS-Q/M11/wiki/index)

#### M10：[资源构建](https://github.com/OS-Q/M10)

用于完成需求资源的初始构建，例如源码编译和模型训练

#### -> M11：[并发处理](https://github.com/OS-Q/M11) 

用于处理特殊状态下的大量事件，扩展相应短板性能

#### M12：[深度加速](https://github.com/OS-Q/M12)

对于庞大、有时限和算力门槛的状态提供算力辅助


---

###  [Q redefined the scope of operation system](http://www.OS-Q.com)
###  qitas@qitas.cn
###  2018-11-29
