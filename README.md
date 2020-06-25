# shoppingForm
asp.net FrameWork架构构建的购物平台

# 0x01 环境说明
	- 代码开发环境为VS2015 pro
	- 官方推荐的数据为SQL Server，建议使用2012（后续调整架构时候可能会重新用回sqlServer）
	- 实际过程中使用了phpstudy中安装的mysql5.7
		- 相对应的，就需要增加mysql5.7对应的数据库连接程序MySql.Data.dll8.0.20版本（https://dev.mysql.com/downloads/connector/net/）
	- 为了更加便于操作数据库，还需要安装navicat作为数据库操作接口软件
	
# 0x02 项目架构

## 数据库
  鉴于使用了mysql作为数据库，后续会将数据库初始化sql文件直接放入软件中，便于假设环境。
  数据库请务必搭建在本地127.0.0.1的回环地址上，用户名为root，密码为123456。

## 平台
  网站主体包括六个页面（）和一个webConfig配置文件。
  六个页面，每个页面分别配属一个.aspx的前端页面和一个.cs的后台。
