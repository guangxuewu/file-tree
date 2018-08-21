使用关系型数据库模拟文件树操作，假设文件树内不包含文件  
#### 应用场景：
大部分需要在关系型数据库中存储树状结构的需求，都可以通过改造本工程实现
#### 支持功能：
* 添加 
* 删除 
* 移动 
* 复制
#### 实现原理：闭包表
参考链接：https://www.jianshu.com/p/951b742fd137
#### 运行：
数据库结构备份在db文件夹中  
功能测试在test文件夹中，列出了大部分功能的测试  
添加Controller，集成前端界面之后可以实现模拟一个文件浏览器    
数据库链接在application.yml中编辑
#### 环境：
jdk8，mysql57
#### 文件树结构：
![文件树](https://raw.githubusercontent.com/fatcats/treedemo/master/tree.png)
