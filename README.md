# socket

## 处理粘包
1.  fix length
发送方，每次发送固定长度的数据，并且不超过缓冲区，接受方每次按固定长度区接受数据

2. delimiter based
发送方，在数据包添加特殊的分隔符，用来标记数据包边界

3. length field based
发送方，在消息数据包头添加包长度信息
