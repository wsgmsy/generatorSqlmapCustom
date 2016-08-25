# mybatis 逆向生成工具
这是一个 mybaits自动生成 model、dao接口、mapper文件的工具，可以为开发节省时间，也挺好用的

1.修改 generatorConfig.xml的jdbcConnection节点，修改数据库链接信息

2.修改 generatorConfig.xml的table节点的tableName属性，跟数据库表名对应

3.修改 generatorConfig.xml的sqlMapGenerator节点的targetPackage属性

4.修改 generatorConfig.xml的javaClientGenerator节点的targetPackage属性

如果下载了spring-mvc的项目，上面的 3和4的targetPackage属性内容只需要修改 com.app.dao.后的名字就行，跟项目是对应的

如果你只是弄工具，那么根据你自己的需要进行修改就可

以上功能弄完以后  直接执行 GeneratorSqlmap.java文件就行了，执行完成刷新一下项目就可以看到生成的文件

