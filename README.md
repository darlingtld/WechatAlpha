# WechatAlpha
An alpha platform for all wechat accounts

系统安装
1、将jeewx压缩包解压并上传到服务器。
2、首次在浏览器中访问 http://localhost:8080/jeewx/，默认admin登录，一个账号只能配置一个微信公众账号。
3、按照安技术文档完成安装，如果有问题请访问官网讨论区寻求帮助。
4、服务器配置      
        URL:   http://*地址*/jeewx/wechatController.do?wechat
        Token:  jeecg（自己配置）

开发者注意事项
1.依赖包下载地址：http://pan.baidu.com/s/1hqviqnq  放入maven repository
2.使用jdk1.7 进行开发，jdk1.8与当前freemarker版本冲突
3.使用mysql数据库，初始数据库脚本在doc中。数据库配置文件在resources\dbconfig.properties
4.还有问题找灵达
