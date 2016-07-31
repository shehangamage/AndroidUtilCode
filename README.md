# Android开发人员不得不收集的代码(不断更新)  
为方便查找，已进行大致归类，其大纲如下所示：  
- [尺寸相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_size.md)
	- dp与px转换
	- sp与px转换
	- 各种单位转换
	- 在onCreate()即可获取View的宽高
	- ListView中提前测量View尺寸
- [手机相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_phone.md)
	- 判断设备是否是手机
	- 获取当前设备的IMIE，需与上面的isPhone一起使用
	- 获取手机状态信息
	- 是否有SD卡
	- 获取MAC地址
	- 获取手机厂商，如Xiaomi
	- 获取手机型号，如MI2SC
	- 跳转至拨号界面
	- 拨打电话
	- 发送短信
	- 获取手机联系人
	- 直接打开手机联系人界面，并获取联系人号码
	- 获取手机短信并保存到xml中
- [网络相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_net.md)
	- 打开网络设置界面
	- 判断是否网络连接
	- 判断wifi是否连接状态
	- 获取移动网络运营商名称，如中国联通、中国移动、中国电信
	- 返回移动终端类型
	- 判断手机连接的网络类型(2G,3G,4G)
	- 判断当前手机的网络类型(WIFI还是2,3,4G)
- [App相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_app.md)
	- 安装指定路径下的Apk
	- 卸载指定包名的App
	- 获取App名称
	- 获取当前App版本号
	- 打开指定包名的App
	- 打开指定包名的App应用信息界面
	- 分享Apk信息
	- 获取App信息的一个封装类(包名、版本号、应用信息、图标、名称等)
	- 判断当前App处于前台还是后台
- [屏幕相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_screen.md)
	- 获取手机分辨率
	- 获取状态栏高度
	- 获取状态栏高度＋标题栏(ActionBar)高度
	- 获取屏幕截图
	- 设置透明状态栏，需在setContentView之前调用
- [键盘相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_keyboard.md)
	- 避免输入法面板遮挡
	- 动态隐藏软键盘
	- 点击屏幕空白区域隐藏软键盘
	- 动态显示软键盘
	- 切换键盘显示与否状态
- [正则相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_regular.md)
	- 正则工具类
- [加解密相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_encrypt.md)
	- MD5加密
	- SHA加密
- [未归类](https://github.com/Blankj/AndroidUtilCode/blob/master/unclassified.md)
	- 获取服务是否开启

大部分代码已验证过可行，如有错误，请及时告之。  
期待你的Star和完善...