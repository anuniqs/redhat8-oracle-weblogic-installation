### GYAN —

#### What is application server  —

An application server is a server that hosts applications. Application server frameworks are software frameworks for building application servers. An application server framework provides both facilities to create web applications and a server environment to run them.

#### What is administration server  —

Administration Server is a WebLogic Server instance that maintains configuration data for a domain.

#### What is managed server —

Managed Server is an instance of your WebLogic server that is running on JVM and has its own configuration.
```
```
### Java installation (Oracle Java) —

**Download site address -** http://www.oracle.com/technetwork/java/javase/downloads/index.html

Which is - jdk-15.0.1_linux-x64_bin.tar.gz

[anup@192 ~]$ java -version

Or,

[anup@192 ~]$ /home/anup/java-15/bin/java -version

```
java version "15.0.1" 2020-10-20
Java(TM) SE Runtime Environment (build 15.0.1+9-18)
Java HotSpot(TM) 64-Bit Server VM (build 15.0.1+9-18, mixed mode, sharing)
```

### Weblogic installation — 

**Download Site address -** https://www.oracle.com/middleware/technologies/fusionmiddleware-downloads.html

Which is - "fmw_14.1.1.0.0_wls_lite_Disk1_1of1.zip"

[anup@192 ~]$ unzip fmw_14.1.1.0.0_wls_lite_Disk1_1of1.zip

[anup@192 ~]$ java -jar fmw_14.1.1.0.0_wls_lite_generic.jar

[root@192 ~]# sudo firewall-cmd --state

[root@192 ~]# sudo systemctl stop firewalld

[root@192 ~]# sestatus

[root@192 ~]# setenforce 0

```
```

### Start Weblogic Server —

[anup@192 ~]$ cd /home/anup/Oracle/Middleware/Oracle_Home/user_projects/domains/base_domain

[anup@192 base_domain]$ ./bin/startWebLogic.sh

http://192.168.43.165:7001/console/

```
UserName - What we set on configuring time (weblogic)
Password - What we set on configuring time (Password+987*)
```

### Configuring Oracle Weblogic Server —

[anup@192 ~]$ cd /home/anup/Oracle/Middleware/Oracle_Home/oracle_common/common/

[anup@192 common]$ ./bin/config.sh
