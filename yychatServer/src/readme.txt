1、使用数据库user表中的用户名和密码进行用户的登录验证：
	思路：在客户端输入用户名和密码，在服务器端接收到用户名和密码后，在数据库中查询user表，
		看看有没有用户名和密码相同的记录，如果有则允许登录，否则不能登录。
		
2、数据库的封装：把和数据库相关的处理放在一个单独的类（YychatDbUtil）中，使得我们的程序逻辑更清晰。
	