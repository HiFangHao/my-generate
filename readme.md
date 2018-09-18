* 通过maven工程产生逆向工程的步骤
1. 通过idea创建maven项目
2. 修改pom.xml
    * 修改依赖：mybatis的核心包，逆向工程包
    * 修改插件：
        * mybatis-generator-maven-plugin
        * configuration
        * executions
        * dependencies
3. 新建src/main/resources/generator.xml
    * 本地mysql驱动包的位置
    * 连接数据库的信息
    * pojo所在位置
    * dao所在位置
    * mapper所在位置
    * 数据库表
4. 执行测试