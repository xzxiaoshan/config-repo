使用URL查看指定配置文件内容的方法：
http://{configserver}:{configserver.port}/{name}/{profile}
------------------------------------------------------------------------
例如我们要查看 sample-cloud-client-test.properties 
则请求的地址为：http://localhost:8888/sample-cloud-client/test
返回的信息按优先顺序包括：sample-cloud-client-test.properties、application-test.properties 和 application.properties
因为 application 被框架认为默认配置文件。