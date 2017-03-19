1、简介
	1.1 名称：weatherSpider-v1.0
	1.2 功能：抓取北京空气质量（http://zx.bjmemc.com.cn）主页数据，获得北京各地区空气质量数据并存储到本地excel文件。
	1.3 语言、环境：java （JDK 1.7）
	1.4 目录简介：
		weatherSpider-v1.0
			|
			+——--bin
			|	 |
			|	 +——com 编译文件.class
			|	 |
			|	 +——EXE.cmd 执行该程序脚本
			|
			+——--lib 依赖的第三方jar包
			|
			+——--result 存放信息结果文件.xls
			|   
			+——--src 
				 |
				 +——com 源文件.java
				 |
				 +——compile.cmd 执行编译脚本


2、使用方法
	2.0 请正确安装JDK；
	2.1 首次使用请双击weatherSpider-v1.0\src\compile.cmd 执行编译脚本，没信息是最好的信息！（此步骤只需执行一次）；
	2.2 编译完成，双击执行weatherSpider-v1.0\bin\EXE.cmd 执行该程序脚本；
	2.3 查看结果，weatherSpider-v1.0\result\存放信息结果文件.xls；
	2.4 如需要定时使用，只要定时执行weatherSpider-v1.0\bin\EXE.cmd。


																						Created by zhouhongfei 
																						2017/3/16 20:09