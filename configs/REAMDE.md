# 配置文件说明

## Models block 名称和参数

``` yaml
backbone:
# [block_type, [args1, args2, ...]]
# i.e. [ResBlock, repeats, [out_channels]]
# i.e. [BottleneckResBlock, repeats, [bottleneck_channels, out_channels]]

head:
# i.e. [FCHead, [hidden_dim1, hidden_dim2, ...]]
# i.e. [Conv1x1Head]
```