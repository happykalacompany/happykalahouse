## composer在ubuntu下的安装
安装的参考地址请[点击](https://docs.phpcomposer.com/00-intro.html#Installation-*nix)

- 1、局部安装  
1.1）下载安装脚本  
``
php -r "copy('https://install.phpcomposer.com/installer', 'composer-setup.php');"
``  
1.2)执行安装脚本  
``
php composer-setup.php
``  
1.3、删除安装脚本  
``
php -r "unlink('composer-setup.php');"
``
- 2、全局安装  
在局部安装的基础上使用如下的命令处理即可实现composer的全局调用
``
sudo mv composer.phar /usr/local/bin/composer
``  
这样之后composer就可以在全局使用了