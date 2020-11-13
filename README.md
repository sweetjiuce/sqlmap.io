# nmap 手册记录使用
- 参数 -m 

	文件中保存url格式，sqlmap会一个一个检测。


	www.target1.com/vuln1.php?q=foobar

	www.target2.com/vuln2.asp?id=1

	www.target3.com/vuln3/id/1*

- 参数 -g

	sqlmap可以测试注入google 的搜索结果中的get参数。

- 参数 --cooike， --load-cookies

	据说可以在web登录的时候使用，没用过现在。

- 参数 --os-shell

	如果该数据库管理员有权限写入文件，可以通过这个参数获取到对方shell。

- 脚本 --script=auth ip

绕开鉴权的脚本，也可以作为检测部分应用的弱口令。

- 脚本 --script=brute ip

提供暴力破解的方式 可以对数据库 smb snmp进行简单的密码暴力猜解。

其他的方式可以通过

[手册参数详情](https://www.cnblogs.com/hongfei/p/3872156.html)
[脚本参数详情](https://blog.csdn.net/u012206617/article/details/85283834)
