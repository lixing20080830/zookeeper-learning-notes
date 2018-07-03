# zookeeper-learning-notes

### Zookeeper 在Windows下的安装<br>

1 安装JDK<br>

2 安装Zookeeper. 在官网http://zookeeper.apache.org/下载zookeeper.我下载的是zookeeper-3.4.10版本<br>

3 解压zookeeper-3.4.10到D:\learning\zookeeper<br>

4 在D:\learning\zookeeper\zookeeper-3.4.10新建data及log目录<br>

5 ZooKeeper的安装模式分为三种，分别为：单机模式（stand-alone）、集群模式和集群伪分布模式。ZooKeeper 单机模式的安装相对比较简单，如果第一次接触ZooKeeper的话，建议安装ZooKeeper单机模式或者集群伪分布模式<br>
  
6 至D:\learning\zookeeper\zookeeper-3.4.10 复制 zoo_sample.cfg 并粘贴到当前目录下，命名zoo.cfg<br>

7 编辑zoo.cfg.修改如下配置 <br>
  dataDir=D:/learning/zookeeper/zookeeper-3.4.10/data<br>
  dataLogDir=D:/learning/zookeeper/zookeeper-3.4.10/log<br>
![Image text](https://github.com/lixing20080830/zookeeper-learning-notes/raw/master/images-folder/1.png)<br>
8  cmd下进入D:\learning\zookeeper\zookeeper-3.4.10\bin目录下运行zkServer.cmd<br>
如下图所示<br>
![Image text](https://github.com/lixing20080830/zookeeper-learning-notes/raw/master/images-folder/2.png)<br>

9 cmd下进入D:\learning\zookeeper\zookeeper-3.4.10\bin目录下运行zkCli.cmd -server 127.0.0.1:2181<br>
如下图所示<br>
![Image text](https://github.com/lixing20080830/zookeeper-learning-notes/raw/master/images-folder/3.png)<br>

参考资料 https://blog.csdn.net/u010317829/article/details/52119281
