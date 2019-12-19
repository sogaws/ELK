# ELK
learn 
2019-11-06 
参考：https://www.cnblogs.com/aresxin/p/8035137.html

ELK是三个开源软件的缩写，分别表示：Elasticsearch , Logstash, Kibana , 它们都是开源软件。新增了一个FileBeat，它是一个轻量级的日志收集处理工具(Agent)，Filebeat占用资源少，适合于在各个服务器上搜集日志后传输给Logstash，官方也推荐此工具。

一、Elasticsearch是个开源分布式搜索引擎，提供搜集、分析、存储数据三大功能。它的特点有：分布式，零配置，自动发现，索引自动分片，索引副本机制，restful风格接口，多数据源，自动搜索负载等。
二、Logstash 主要是用来日志的搜集、分析、过滤日志的工具，支持大量的数据获取方式。一般工作方式为c/s架构，client端安装在需要收集日志的主机上，server端负责将收到的各节点日志进行过滤、修改等操作在一并发往elasticsearch上去。
三、Kibana 也是一个开源和免费的工具，Kibana可以为 Logstash 和 ElasticSearch 提供的日志分析友好的 Web 界面，可以帮助汇总、分析和搜索重要数据日志。
四、Filebeat隶属于Beats。目前Beats包含四种工具：
   1、Packetbeat（搜集网络流量数据）
   2、Topbeat（搜集系统、进程和文件系统级别的 CPU 和内存使用情况等数据）
   3、Filebeat（搜集文件数据）
   4、Winlogbeat（搜集 Windows 事件日志数据）
   
   
一、Elasticsearch学习：
elasticsearch中文社区：
https://elasticsearch.cn/
