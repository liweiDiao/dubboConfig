# dubboConfig
springboot dubbo yml配置

dubbo:    
&nbsp;&nbsp;annotation:</br>
&nbsp;&nbsp;&nbsp;&nbsp;package: com.cnd </br>
&nbsp;&nbsp;container: log4j,spring </br>
&nbsp;&nbsp;application: </br>
&nbsp;&nbsp;&nbsp;&nbsp;name: operational-service </br>
&nbsp;&nbsp;&nbsp;&nbsp;owner: cnd </br>
&nbsp;&nbsp;registry: </br>
&nbsp;&nbsp;&nbsp;&nbsp;address: zookeeper://192.168.153.1:2181</br>
&nbsp;&nbsp;provider: </br>
&nbsp;&nbsp;&nbsp;&nbsp;timeout: 30000 </br>
&nbsp;&nbsp;&nbsp;&nbsp;port: 25999 </br>
&nbsp;&nbsp;consumer: </br>
&nbsp;&nbsp;&nbsp;&nbsp;timeout: 30000 </br>
&nbsp;&nbsp;&nbsp;&nbsp;check: false </br>
&nbsp;&nbsp;&nbsp;&nbsp;retries: 0 </br>
&nbsp;&nbsp;protocol: </br>
&nbsp;&nbsp;&nbsp;&nbsp;name: dubbo </br>
&nbsp;&nbsp;&nbsp;&nbsp;threadpool: cached </br>
&nbsp;&nbsp;&nbsp;&nbsp;threads: 500 </br>
&nbsp;&nbsp;&nbsp;&nbsp;accepts: 1000 </br>
&nbsp;&nbsp;&nbsp;&nbsp;dispatcher: message </br>
&nbsp;&nbsp;service: </br>
&nbsp;&nbsp;&nbsp;&nbsp;loadbalance: roundrobin</br>
