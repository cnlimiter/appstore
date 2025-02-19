# Redpanda Console

Redpanda Console 是一个开发人员友好的 UI，用于管理 Kafka/Redpanda 工作负载。控制台为您提供了一种简单的交互式方法，用于了解主题、屏蔽数据、管理消费者组以及通过时间旅行调试探索实时数据。

## 主要功能：

- 消息查看器：通过即席查询和动态过滤器在我们的消息查看器中探索您的主题消息。使用 JavaScript 函数过滤消息来查找您想要的任何消息。支持的编码有：JSON、Avro、Protobuf、XML、MessagePack、Text 和 Binary（十六进制视图）。使用的编码（Protobuf 除外）会自动识别。 
-  消费者组：列出所有活动消费者组及其活动组偏移量、编辑组偏移量（按组、主题或分区）或删除消费者组。 
- 主题概述：浏览 Kafka 主题列表，检查其配置、空间使用情况、列出使用单个主题的所有消费者或观察分区详细信息（例如低水位线和高水位线、消息计数等）、嵌入主题来自 git 存储库的文档等等。 
- 集群概述：列出 ACL、可用代理、其空间使用情况、机架 ID 和其他信息，以获得集群中代理的高级概述。 
- 模式注册表：列出模式注册表中的所有 Avro、Protobuf 或 JSON 模式。
- Kafka 连接：管理来自多个连接集群的连接器、修补配置、查看其当前状态或重新启动任务。