### DEBUG启动Tomcat源码--操作步骤
在Eclipse 中的 Debug Configurations 中加入一个启动 Tomcat 的 Appliction. <br>
具体在 Java Application 中加入Main启动项，选择刚才导入的 Tomcat 7.0项目，<br>
Main class 填写 org.apache.catalina.startup.Bootstrap启动类，<br>
然后选择 Arguments ，在 Program arguments 填写  start, <br>
在 VM arguments 中填写 tomcat home 的路径，如：-Dcatalina.home=C:\tomcat-7.0.42-sourcecode

http://denger.iteye.com/blog/834121

有问题发邮件 chengzhx76@qq.com
