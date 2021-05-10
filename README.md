https://github.com/gotomicro/ego

git submodule add https://github.com/gotomicro/ego

 go mod init echo_learn

 export EGO_DEBUG=true
 go run main.go --config=config.toml

 https://ego.gocn.vip/

 https://github.com/gotomicro/egoctl

 框架分为三个层次

核心层提供配置、日志、监控和链路，是其他组件的基石
组件层提供客户端、服务端、任务端里的各种组件
胶水层控制了各种组件的生命周期，错误处理