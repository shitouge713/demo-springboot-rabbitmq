# demo-springboot-rabbitmq
RabbitMQ 消息队列、死信队列及延时队列（包括RabbitMQ延时插件）的使用


### RabbitMQ的安装与配置
http://liangtong.site/2020/09/14/java_20200914_rabbitmq_config/

### RabbitMQ消息队列
http://liangtong.site/2020/09/15/java_20200915_springboot_rabbitmq_im/

### RabbitMQ死信队列
http://liangtong.site/2020/09/16/java_20200916_springboot_rabbitmq_dead/


### RabbitMQ延时队列
http://liangtong.site/2020/09/16/java_20200916_springboot_rabbitmq_delay/


# 请求
http://localhost:8081/rabbitmq/send?msg=123
http://localhost:8081/rabbitmq/fixDelay1?msg=234
http://localhost:8081/rabbitmq/fixDelay2?msg=456&delay=2
http://localhost:8081/rabbitmq/delay?msg=789&delay=5