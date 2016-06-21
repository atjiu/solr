> 安装好ik分词器与拼音分词器的solr

版本：

- jdk1.8
- solr6.0.1
- tomcat8

## 使用说明

clone 代码

```
https://github.com/tomoya92/solr.git
```

打开 `apache-tomcat-8.0.35/webapps/solr/WEB-INF/web.xml` 修改 `{solr_home}` 为clone下来保存在本地的 solr_home 

启动tomcat

**注意：使用高亮就不要开拼音检索，使用拼音就不要开高亮**

## 案例

http://bbs.tomoya.cn

源码地址：https://github.com/tomoya92/pybbs.git

索引，查询工具：https://github.com/tomoya92/pybbs/blob/master/src/main/java/cn/tomoya/utils/SolrUtil.java

## 相关资料

http://bbs.tomoya.cn/t/34
