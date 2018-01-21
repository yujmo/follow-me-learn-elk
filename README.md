# elk安装与配置  #

## elk简介 ##

    - Elastic Stack，是一种能够从任意数据源抽取数据，并实时对数据进行搜索、分析和可视化展现的数据分析框架。
    - elk的组成：ElasticSearch、Logstash和Kiabana
        * Elasticsearch：开源分布式搜索引擎，分布式，零配置，自动发现，索引自动分片，索引副本机制，restful风格接口，多数据源，自动搜索负载等。
        * Logstash，对日志进行收集、过滤，并将其存储供以后使用。
        * Kibana，为 Logstash 和 ElasticSearch 提供的日志分析友好的 Web 界面，汇总、分析和搜索重要数据日志。
