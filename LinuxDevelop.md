1. 下载jdk
   wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" 
   /* jdk url */
2. 解压tar 
   tar -xzvf 文件名
   
3. 配置环境变量 vi /etc/proflie
   export JAVA_HOME=/home/jdk/jdk1.8.0_161
   export PATH=$JAVA_HOME/bin:$PATH
   export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
   
4. 下载tomcat 
   wget https://mirrors.cnnic.cn/apache/tomcat/*

5. 解压 启动 
