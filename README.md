# 为Pinpoint开发的Dubbo插件

## 使用方法

编译项目

```
mvn package
```

输出的`$PLUGIN_HOME/agent/target/pinpoint-agent-$VERSION`目录作为agent

将`$PLUGIN_HOME/agent/target/pinpoint-agent-$VERSION/plugin/pinpoint-dubbo-plugin-$VERION.jar`拷贝到collector和web的lib目录中

# 为Pinpoint开发的RabbitMQ插件

## 使用方法

同上

# 建议

建议将代码改到pinpoint项目的plugins模块下,否则server map上面的图标无法显示