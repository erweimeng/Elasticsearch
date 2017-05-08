Elasticsearch-1.7.0安装手册

解压elasticsearch-1.7.0.tar.gz 软件包.
#tar zxf elasticsearch-1.7.0.tar.gz


es配置文件参数(不全用的到)：

#集群名称标识了你的集群，自动探查会用到它。
#如果你在同一个网络中运行多个集群，那就要确保你的集群名称是独一无二的.
cluster.name: test-elasticsearch


#节点名称会在启动的时候自动生成，所以你可以不用手动配置。你也可以给节点指定一个特定的名称.
node.name: "elsearch1"

#允许这个节点被选举为一个主节点(默认为允许)
#node.master: true

#允许这个节点存储数据(默认为允许)
#node.data: true

#You can exploit these settings to design advanced cluster topologies.


