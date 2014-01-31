Danted Socks5 一键安装脚本

******功能特点
1. 采用最新稳定版本 1.4.0 编译安装。
2. 自动识别系统IP（默认排除192.168.0.*， 10.0.0.*,127.0.0.*）,检测多Ip时，进行交互式选择Ip配置（直接回车则全部配置）。
3. 采用Pam用户认证，认证不需要添加系统用户（默认添加进程用户sock），删除、添加用户方便，安全。
4. sock5 运行状态查看。
5. 系统启动后自动加载。
6. 认证方式可选： 无用户名密码，系统用户名密码，Pam用户名密码
7. 完美支持Centos/Debian

******未解决问题
1. sock5多用户验证策略，在只是用一个配置文件的情况下，指定了采用用户认证，则无法指定某些Ip段无需认证即可连接。
2. 分析lo对连接sock5的用户进行统计。
3. 自动识别系统进行安装配置。
