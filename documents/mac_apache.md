Mac 自带Apache的使用
===================

1.	mac osx下apache的目录在`/etc/apache2`
2.	修改默认部署路径 apache2/httpd.conf 找到DocumentRoot(sudo vim,文件只读需要root权限修改)
3.	修改访问权限，`Require all denied => Require all granted`

		<Directory />
		    AllowOverride none
		    Require all granted
		</Directory>
		
4.	开启／停止apache服务 `sudo apachectl start/restart/stop`