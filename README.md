# go_distributed_system
自己动手实现分布式系统

测试方法：
    cd ./bin

    1. 启动master  ./distributed --makeMasterOnError true
    
    2. 启动worker1 ./distributed  --myport 8002 --clusterip 127.0.0.1:8001
