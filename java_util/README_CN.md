#　说明

1. dubbo-go-hessian2 中 UUID 目前解析情况
- uuid.go 中提供了解析 Java 中生成好的 UUID 对象，测试通过，但是不提供生成 UUID 的功能
- java-server 提供的 uuid 可以解析，可以通过 UUID 的 ToString()函数解析成字符串，但是 go 目前未提供生成 uuid 的功能
- java uuid 生成可以参考 jdk 下 java.util.UUID 类的相关源码
- uuid 结构体创建参考 https://github.com/satori/go.uuid
