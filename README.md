**PS: pybbs最新版本使用了hibernate-search，不需要另外再配置检索，强烈建议将pybbs升级到最新版**

## 介绍

安装好ik分词器与拼音分词器的solr

## 依赖

- jdk1.8
- solr6.0.1
- tomcat8

## 使用说明

clone 代码

```
git clone https://github.com/tomoya92/solr.git
```

打开 `apache-tomcat-8.0.35/webapps/solr/WEB-INF/web.xml` 修改 `{solr_home}` 为clone下来保存在本地的 solr_home 

启动tomcat

**注意：使用高亮就不要开拼音检索，使用拼音就不要开高亮**

源码地址：https://github.com/tomoya92/pybbs/tree/v2.3

索引，查询工具：https://github.com/tomoya92/pybbs/blob/v2.3/src/main/java/cn/tomoya/utils/SolrUtil.java

## 相关资料

[https://github.com/tomoya92/pybbs/wiki/2.3版本-配置solr检索](https://github.com/tomoya92/pybbs/wiki/2.3%E7%89%88%E6%9C%AC-%E9%85%8D%E7%BD%AEsolr%E6%A3%80%E7%B4%A2)
