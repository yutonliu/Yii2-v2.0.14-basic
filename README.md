# Notices:
~~~
1. yii2.0.14.zip 为原始官网文件

2. yii2.tar 为直接可以使用的 composer install过的 有vendor的 版本

~~~

### 版本1 修正方法(yii2.0.14.zip)
~~~
$ unzip yii2.0.14.zip #解压文件
$ mv yii2-app-basic-2.0.14  yii2-app-basic #修改名字
$ cd yii2 #进入目录内
$ composer install #安装相关依赖包
`composer install 如果出现 rate limit或者 token无效的情况 可以看此解决方法
https://stackoverflow.com/questions/27809909/installing-yii2-via-composer-and-it-keeps-prompting-for-a-password
自己去github上申请一个token 然后填到里面
`
~~~

#### 安装完composer 会出现一个vendor文件  

####  ip地址访问 http://192.l68.0.169/yii2-app-basic/web/

#### 报错解决方法

1. `安装使用报错：cookieValidationKey `

http://www.yiichina.com/tutorial/554

2. `其他的如果 没有写的权限 或者创建的权限的话 把报错的文件 权限给为 777`


