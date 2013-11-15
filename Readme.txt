代码使用说明：
	功能：
		1、对图片文件夹和图片文件进行拷贝，分为源文件夹和目标文件夹，在文件夹中可以包含多文件夹和文件；
		2、数据库分为供体库和受体库，供体库提供数据信息，受体库接收数据信息；
		3、在代码中，供体库数据库名为：myuser,其中有一张表staff；
		4、表中字段a1-a15和d1-d16变量对应关系以及中文代表：
		（注：下面表示的意思，如a1->d1->cat_id[分类编号]表示从供体库（mmpro）取字段a1保存在d1变量中，再将d1变量写入到受体库（mmpro shop）的cat_id[分类编号]字段）
								a1->d1->cat_id[分类编号]，
								a2->d2->goods_sn[商品货号]，
								a3->d3->goods_name[商品名称]，
								a4->d4->brand_id[品牌ID]，
								a5->d5->provider_name[供货商名称]，
								a6->d6->goods_number[库存数量]，
								a7->d7->goods_weight[商品重量]，
								a8->d8->market_price[市场价格]，
								a9->d9->shop_price[商店售价]，
								a10->d10->goods_brief[商品简单说明]，
								a11->d11->goods_desc[详细描述]，
								a12->d12->goods_thumb[缩略图链接地址]，
								a13->d13->goods_img[图片链接地址]，
								a14->d14->original_img[商品原始图片地址]，
								a15->d15->goods_type[商品类型ID].
		5、供体库myuser中数据表staff中的字段介绍（注：只供测试用）：
 				字段	类型				整理					Null	默认		额外	
				ID		int(11)								否			 	 自增	 	 	 	 	
				a1		int(2)								是		NULL		 	 	 	 	 	 	
				a2		varchar(50)		utf8_general_ci		是		NULL		 	 	 	 	 	 	 
				a3		varchar(5)		utf8_general_ci		是		NULL		 	 	 	 	 	 	 
				a4		int(3)								是		NULL		 	 	 	 	 	 	
				a5		varchar(50)		utf8_general_ci		是		NULL		 	 	 	 	 	 	 
				a6		int(3)								是		NULL		 	 	 	 	 	 	
				a7		int(3)								是		NULL		 	 	 	 	 	 	
				a8		int(5)								否			 	 	 	 	 	 	
				a9		int(5)								否			 	 	 	 	 	 	
				a10		varchar(50)		utf8_general_ci		否			 	 	 	 	 	 	 
				a11		varchar(50)		utf8_general_ci		否			 	 	 	 	 	 	 
				a12		varchar(50)		utf8_general_ci		否			 	 	 	 	 	 	 
				a13		varchar(50)		utf8_general_ci		否			 	 	 	 	 	 	 
				a14		varchar(50)		utf8_general_ci		否			 	 	 	 	 	 	 
				a15		int(5)								否			 	 	 	 	 	 	
		








注意：本项目可用myeclipse导入，导入成功后请先将mysql的jdbc驱动加入到项目中（mysql-connector-java-5.0.3-bin）才可正常运行本项目。
		
东华理工大学IT网项目组相关链接
==========================================================================================================================
    东华理工大学IT网：
http://ecit-it.com
            
http://www.ecit-it.com

    东华理工大学IT网团队项目协同办公室：
http://ecit-it.tudu.im/

    东华理工大学IT网站官方微博：
http://e.weibo.com/1910620900/ 
                
http://weibo.com/lhd20111102

    东华理工大学IT网站博客：
http://blog.sina.com.cn/ulihd

    东华理工大学IT网站博客手机端下载链接：
http://s.hudee.com/1910620900

    东华理工大学IT网移动客户端下载：
http://app.zhui.cn/Mobile/Down.aspx?SID=79935&SwitchOS=1
                    
http://www.ecit-it.com/a/ITchuangyi/20130429/1422.html

    东华理工大学IT网网站站长简历：
http://www.ecit-it.com/a/ITjiuye/20130428/1395.html

    东华理工大学IT网QQ交流群：
                             37604517
