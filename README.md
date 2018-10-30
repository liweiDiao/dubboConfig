# dubboConfig
springboot dubbo yml配置

dubbo: 
    annotation: 
           package: com.cnd 
    container: log4j,spring 
    application: 
           name: operational-service 
           owner: cnd 
    registry: 
          address: zookeeper://192.168.153.1:2181
    provider: 
         timeout: 30000 
         port: 25999 
    consumer: 
         timeout: 30000 
         check: false 
         retries: 0 
    protocol: 
         name: dubbo 
         threadpool: cached 
         threads: 500 
         accepts: 1000 
         dispatcher: message 
    service: 
           loadbalance: roundrobin
