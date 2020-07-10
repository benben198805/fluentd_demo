# fluentd_demo

## etc/*.conf
测试不同的配置

## docker测试
* docker-compose up --build fluentd
* docker-compose up httpd
  * 可能会出现：WARNING: no logs are available with the 'fluentd' log driver，需要等待httpd找到fluentd
* 访问http://localhost:5000/，产生日志
* 配置kibana后，可以访问:http://localhost:5601，查看日志
