### 常用命令    

> 清屏

	clear：清除屏幕信息


> 切换身份

	su -：切换身份
	
	exit：切换身份后退出切换到的身份，回到原来的身份


> 路径

	./：当前路径
	../：上级路径
	/usr/local：绝对路径



> 多个指令 依次执行，中间使用分号[;]隔开

	ls -l; cat /etc/issue


> 获取路径的文件名称和目录名称

	basename 路径：这个是获取路径的名称
		basename /etc/sysconfig/network  -->  network
		
	dirname 路径：这个是获取路径的 路径
		dirname	 /etc/sysconfig/network	 -->  /etc/sysconfig



> 关机

	sync：同步修改到磁盘
	
	reboot：重启
	
	halt/poweroff：关机
	
	shutdown：命令
	
		-t second：-t 后面加秒数， 过几秒后关机
		
		-k msg：不是真的关机，只是发送警告信息
		
		-r：在系统停掉服务后重启
		
		-h：将系统服务停掉后，立即关机
		
		-n：不经过 init程序，直接以 shutdown 的功能关机
		
		-f：关机并启动走后，签字略过 fsck 的磁盘检测
		
		-F：系统重启后，强制进行 fsck 的磁盘检测
		
		-c：取消已经在进行的 shutdown 命令内容
		
		具体时间：这是所有命令后面都要加入的参数，指定系统关机的时间  now  3  20:40  +20



> 帮助文档

	[cmd] --help：查看简单帮助
	
	man [cmd]：在线详细文档
	
		Shift+PageUp：上一页
		
		Shift+PageDown：下一页
		
		Space：向下翻
		
		E：向下翻

	info [cmd]：同 man



> 编辑器

	nano：超简单编辑器
	
	vim		
	
	touch：创建空文件
