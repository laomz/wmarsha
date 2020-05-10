# wmarsha 极限序列化工具

# 与google.protobuf对比测试

Marshal速度是pb的9～33倍

Unmarsha速度是pb的105～263倍

Marshal得到的字节流是pb的27%～72%

内存占用是pb的21%～93%

Marshal的cpu占用是pb的102%～320%

Unmarsha的cpu占用是pb的79%～211%

Marshal与Unmarsha的cpu占用是pb的79%～320%，其中大于100%的概率为73%，优化工作还在进行中。

测试环境及数据，测试案例将在发布一起上传。

# 目前只完成了go的实现版本，后续将对c/c++，java，js，python，c#，lua，typescript等语言进行支持
# 开源发布工作还在继续中，敬请关注...
