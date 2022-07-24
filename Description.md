Mysql：用户名: root
              密码: 
              连接:mysql -u root -p
		启动服务
		mysql.server start
		关闭服务
		mysql.server stop
		重启服务
		mysql.server restart
		brew services start mysql
		brew services stop mysql
		brew services restart mysql


Datascrip IDE: 账户:
			    密码:

PostgreSQL: 
	        用户名: postgres
	        密码：  
 
Mongodb:
		To start mongodb:
		brew services start mongodb-community
		To stop mongodb if it's already running:
		brew services stop mongodb-community
    To run MongoDB (i.e. the mongod process) as a macOS service, run:
    brew services start mongodb-community@5.0
    To stop a mongod running as a macOS service, use the following command as needed:
    brew services stop mongodb-community@5.0

Chromedriver:
chromedriver --version
brew update
brew cask upgrade chromedriver
