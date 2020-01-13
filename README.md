# RocketMQ
> 使用 RocketMQ 需要先启动 nameServer 和 broker，分别由对应的两个模块提供。启动两个模块前：
>
> 1. 在项目根目录下新建目录 /conf
> 2. 由 distribution 模块中复制 broker.conf、logback_broker.xml、logback_namesrv.xml 至 /conf/ 目录下
> 3. 配置 namesrv 模块：在 IDEA 中配置环境变量 ROCKETMQ_HOME = /project-directory/rocketmq
> 4. 配置 broker 模块：需要在 IDEA 中指定启动参数 -c /project-directory/rocketmq/conf/broker.conf
> 5. 配置完之后，分别启动：NamesrvStartup  和 BrokerStartup
> 6. 测试时，启动生产者发送消息：example.quickstart.Producer
> 7. 另外，下载可视化代码：rocketmq-externals，启动其中的模块 rocketmq-console，访问 RocketMQ 控制台
## nameServer 模块

## broker 模块
