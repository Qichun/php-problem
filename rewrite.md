#### htaccess文件不起作用
#### 第一步
##### 打开httpd.conf 文件，查看apache是否加载了rewrite 模块，LoadModule rewrite_module modules/mod_rewrite.so
#### 第二步
##### 查看对应虚拟域名的配置，查看AllowOverride None 还是AllowOverride All，AllowOverride All是允许htaccess文件起作用的
##### 第三步
##### 检查对应的htaccess文件的rewrite engine是否打，RewriteEngine On
