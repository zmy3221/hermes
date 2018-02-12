### 基于springcloudconfig和gitlab的配置中心可视化项目接口

----------------------------------------------------------

#### 目的：

* 微服务中配置中心是不可或缺的一环，在服务特别多的情况下，配置的管理就会变的很复杂， 项目中可能出现了各种配置来回复制的情况，hermes是基于spring cloud config的图形化配置管理工具.

#### 特点

 * 多级配置，该项目中把配置文件分为四个层级，利用继承，实现了所有项目的共有配置，环境的共有配置，项目共有配置，项目环境配置
 * 图形化管理界面
 * 与gitlab结合

#### 技术

 * 后端：python + flask
 * 前端： react
