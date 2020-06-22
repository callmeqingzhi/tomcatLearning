## 源码构建
#### jvm参数
idea设置Bootstrap类启动jvm参数如下：
-Dcatalina.home=E:\ideaprojct\apache-tomcat-8.5.56-src/source
-Dcatalina.base=E:\ideaprojct\apache-tomcat-8.5.56-src/source
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
-Djava.util.logging.config.file=E:\ideaprojct\apache-tomcat-8.5.56-src/source/conf/logging.properties

#### ContextConfig类 初始化jsp引擎
 // 初始化jsp引擎
 context.addServletContainerInitializer(new JasperInitializer(), null);



