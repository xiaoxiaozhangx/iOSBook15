### 《iOS开发指南第5版》代码。

* 本书采用OC&Swift双语言对照。
* Swift 3.x以上。
* Xcode 8以上。
* iOS 10.3以上。
* 图书服务网站：http://www.51work6.com/forum.php?mod=forumdisplay&fid=100
* 视频平台：http://www.zhijieketang.com
* QQ交流群：162030268
* 邮箱：eorient@sina.com
* 新浪微博：tony_关东升

### 《iOS开发指南第5版》目录

###### 第1章        开篇综述
######         1.1　iOS概述
######                 1.1.1　iOS介绍
######                 1.1.2　iOS 10新特性
######         1.2　开发环境及开发工具
######         1.3　本书约定
######                 1.3.1　案例代码约定
######                 1.3.2　图示的约定
######                 1.3.3　方法命名约定
######                 1.3.4　构造函数命名约定
######                 1.3.5　错误处理约定
###### 
###### 第2章        第一个IOS应用程序
######         2.1　创建HelloWorld工程
######                 2.1.1　通过Xcode创建工程
######                 2.1.2　添加标签
######                 2.1.3　运行应用
######                 2.1.4　Xcode中的iOS工程模板
######                 2.1.5　应用剖析
######         2.2　应用生命周期
######                 2.2.1　非运行状态——应用启动场景
######                 2.2.2　点击Home键——应用退出场景
######                 2.2.3　挂起重新运行场景
######                 2.2.4　内存清除：应用终止场景
######         2.3　设置产品属性
######                 2.3.1　Xcode中的工程和目标
######                 2.3.2　设置常用的产品属性
######         2.4　iOS API简介
######                 2.4.1　API概述
######                 2.4.2　如何使用API帮助文档
######         2.5　小结
###### 
###### 第3章        COCOA TOUCH框架与构建 应用界面
######         3.1　视图控制器
######                 3.1.1　视图控制器种类
######                 3.1.2　视图的生命周期
######         3.2　视图
######                 3.2.1　UIView继承层次结构
######                 3.2.2　视图分类
######                 3.2.3　应用界面构建层次
######         3.3　使用故事板构建界面
######                 3.3.1　什么是故事板
######                 3.3.2　场景和过渡
######         3.4　使用XIB文件构建界面
######                 3.4.1　重构HelloWorld
######                 3.4.2　XIB与故事板比较
######         3.5　使用纯代码构建界面
######                 3.5.1　重构HelloWorld
######                 3.5.2　视图的几个重要属性
######         3.6　三种构建界面技术讨论
######                 3.6.1　所见即所得
######                 3.6.2　原型驱动开发
######                 3.6.3　团队协同开发
######         3.7　小结
###### 
###### 第4章        UIVIEW与视图
######         4.1　标签与按钮
######                 4.1.1　Interface Builder实现
######                 4.1.2　代码实现
######         4.2　事件处理
######                 4.2.1　Interface Builder实现
######                 4.2.2　代码实现
######         4.3　访问视图
######                 4.3.1　Interface Builder实现
######                 4.3.2　代码实现
######         4.4　TextField和TextView
######                 4.4.1　Interface Builder实现
######                 4.4.2　代码实现
######                 4.4.3　键盘的打开和关闭
######                 4.4.4　关闭和打开键盘的通知
######                 4.4.5　键盘的种类
######         4.5　开关控件、分段控件和滑块控件
######                 4.5.1　开关控件
######                 4.5.2　分段控件
######                 4.5.3　滑块控件
######         4.6　Web视图：WKWebView类
######         4.7　警告框和操作表
######                 4.7.1　使用UIAlertController实现警告框
######                 4.7.2　使用UIAlertController实现操作表
######         4.8　等待相关的控件与进度条
######                 4.8.1　活动指示器ActivityIndicatorView
######                 4.8.2　进度条ProgressView
######         4.9　工具栏和导航栏
######                 4.9.1　工具栏
######                 4.9.2　导航栏
######         4.10　小结
###### 
###### 第5章        委托协议、数据源协议与高级视图
######         5.1　视图中的委托协议和数据源协议
######         5.2　选择器
######                 5.2.1　日期选择器
######                 5.2.2　普通选择器
######                 5.2.3　数据源协议与委托协议
######         5.3　集合视图
######                 5.3.1　集合视图的组成
######                 5.3.2　集合视图数据源协议与委托协议
######         5.4　案例：奥运会比赛项目
######                 5.4.1　创建工程
######                 5.4.2　自定义集合视图单元格
######                 5.4.3　添加集合视图
######                 5.4.4　实现数据源协议
######                 5.4.5　实现委托协议
######         5.5　小结
###### 
###### 第6章        表视图
######         6.1　概述
######                 6.1.1　表视图的组成
######                 6.1.2　表视图的相关类
######                 6.1.3　表视图分类
######                 6.1.4　单元格的组成和样式
######                 6.1.5　数据源协议与委托协议
######         6.2　简单表视图
######                 6.2.1　实现协议方法
######                 6.2.2　UIViewController根视图控制器
######                 6.2.3　UITableViewController根视图控制器
######         6.3　自定义表视图单元格
######                 6.3.1　Interface Builder实现
######                 6.3.2　代码实现
######         6.4　添加搜索栏
######         6.5　分节表视图
######                 6.5.1　添加索引
######                 6.5.2　分组
######         6.6　插入和删除单元格
######                 6.6.1　Interface Builder实现
######                 6.6.2　代码实现
######         6.7　移动单元格
######         6.8　表视图UI设计模式
######                 6.8.1　分页模式
######                 6.8.2　下拉刷新模式
######                 6.8.3　下拉刷新控件
######         6.9　小结
###### 
###### 第7章        界面布局
######         7.1　界面布局概述
######                 7.1.1　表单布局模式
######                 7.1.2　列表布局模式
######                 7.1.3　网格布局模式
######         7.2　iOS中各种“栏”
######         7.3　传统界面布局问题
######         7.4　Auto Layout布局技术
######                 7.4.1　在Interface Builder中管理Auto Layout约束
######                 7.4.2　案例：Auto Layout布局
######         7.5　静态表布局
######                 7.5.1　什么是静态表
######                 7.5.2　案例：iMessage应用登录界面
######         7.6　使用堆视图StackView
######                 7.6.1　堆视图与布局
######                 7.6.2　案例：堆视图布局
######         7.7　小结
###### 
###### 第8章        屏幕适配
######         8.1　iOS 屏幕的多样性
######                 8.1.1　iOS屏幕介绍
######                 8.1.2　iOS的3种分辨率
######                 8.1.3　获得iOS设备的屏幕信息
######         8.2　Size Class与iOS多屏幕适配
######                 8.2.1　在Xcode 6和Xcode 7中使用Size Class技术
######                 8.2.2　Size Class的九宫格
######                 8.2.3　Size Class的四个象限
######                 8.2.4　在Xcode 8中使用Size Class
######                 8.2.5　案例：使用Size Class
######         8.3　资源目录与图片资源适配
######         8.4　小结
###### 
###### 第9章        视图控制器与导航模式
######         9.1　概述
######                 9.1.1　视图控制器的种类
######                 9.1.2　导航模式
######         9.2　模态视图
######                 9.2.1　Interface Builder实现
######                 9.2.2　代码实现
######         9.3　平铺导航
######                 9.3.1　应用场景
######                 9.3.2　基于分屏导航的实现
######                 9.3.3　基于电子书导航的实现
######         9.4　标签导航
######                 9.4.1　应用场景
######                 9.4.2　Interface Builder实现
######                 9.4.3　代码实现
######         9.5　树形结构导航
######                 9.5.1　应用场景
######                 9.5.2　Interface Builder实现
######                 9.5.3　代码实现
######         9.6　组合使用导航模式
######                 9.6.1　应用场景
######                 9.6.2　Interface Builder实现
######                 9.6.3　代码实现
######         9.7　小结
###### 
###### 第10章        IPAD应用开发
######         10.1　iPad与iPhone应用开发的差异
######                 10.1.1　应用场景不同
######                 10.1.2　导航模式不同
######                 10.1.3　API不同
######         10.2　iPad树形结构导航
######                 10.2.1　“邮件”应用中的树形结构导航
######                 10.2.2　Master-Detail应用程序模板
######                 10.2.3　使用Interface Builder实现SplitViewSample案例
######                 10.2.4　使用代码实现SplitViewSample案例
######         10.3　iPad模态视图
######                 10.3.1　“邮件”应用中的模态导航
######                 10.3.2　iPad模态导航相关API
######                 10.3.3　使用Interface Builder实现ModalViewSample案例
######                 10.3.4　使用代码实现ModalViewSample案例
######         10.4　Popover视图
######                 10.4.1　Popover相关API
######                 10.4.2　PopoverViewSample案例
######         10.5　分屏多任务
######                 10.5.1　Slide Over多任务
######                 10.5.2　分屏视图多任务
######                 10.5.3　画中画多任务
######         10.6　iPad分屏多任务适配开发
######                 10.6.1　分屏多任务前提条件
######                 10.6.2　分屏多任务适配
######         10.7　小结
###### 
###### 第11章        手势识别
######         11.1        手势种类
######         11.2        手势识别器
######                 11.2.1        视图对象与手势识别
######                 11.2.2        手势识别状态
######                 11.2.3        实例：识别Tap（单击）手势
######                 11.2.4        实例：识别Long Press（长按）手势
######                 11.2.5        实例：识别Pan（平移）手势
######                 11.2.6        实例：Swipe（滑动）手势
######                 11.2.7        实例：Rotation（旋转）手势
######                 11.2.8        实例：Pinch（手指的合拢和张开）手势
######                 11.2.9        实例：Screen Edge Pan（屏幕边缘平移）手势
######         11.3        小结
###### 
###### 第12章        Quartz 2D绘图技术
######         12.1        绘制技术基础
######                 12.1.1        视图绘制周期
######                 12.1.2        实例：填充屏幕
######                 12.1.3        填充与描边
######                 12.1.4        绘制图像和文本
######         12.2        Quartz图形上下文
######         12.3        Quartz路径
######                 12.3.1        Quartz路径概述
######                 12.3.1        实例：使用贝塞尔曲线
######         12.4        Quartz坐标变换
######                 12.4.1        坐标系
######                 12.4.2        2D图形的基本变换
######                 12.4.3        CTM变换
######                 12.4.4        仿射（affine）变换
######         12.5        本章小结
###### 
###### 第13章        动画技术
######         13.1        视图动画
######                 13.1.1        动画块
######                 13.1.2        动画结束的处理
######                 13.1.3        过渡动画
######         13.2        Core Animation框架
######                 13.2.1        图层
######                 13.2.2        隐式动画
######                 13.2.3        显式动画
######                 13.2.4        关键帧动画
######                 13.2.5        使用路径
######         13.3        本章小结
###### 
###### 第14章        数据持久化
######         14.1　概述
######                 14.1.1　沙箱目录
######                 14.1.2　持久化方式
######         14.2　实例：MyNotes应用
######         14.3　属性列表
######         14.4　使用SQLite数据库
######                 14.4.1　SQLite数据类型
######                 14.4.2　添加SQLite3库
######                 14.4.3　配置Swift环境
######                 14.4.4　创建数据库
######                 14.4.5　查询数据
######                 14.4.6　修改数据
######         14.5　iOS 10中的Core Data技术
######                 14.5.1　对象关系映射技术
######                 14.5.2　添加Core Data支持
######                 14.5.3　Core Data栈
######         14.6　案例：采用Core Data重构MyNotes应用
######                 14.6.1　建模和生成实体
######                 14.6.2　Core Data栈DAO
######                 14.6.3　查询数据
######                 14.6.4　修改数据
######         14.7　小结
###### 
###### 第15章        数据交换格式
######         15.1　XML数据交换格式
######                 15.1.1　XML文档结构
######                 15.1.2　解析XML文档
######         15.2　案例：MyNotes应用读取XML数据
######                 15.2.1　使用NSXML解析
######                 15.2.2　使用TBXML解析
######         15.3　JSON数据交换格式
######                 15.3.1　JSON文档结构
######                 15.3.2　JSON数据编码/解码
######         15.4　案例：MyNotes应用JSON解码
######         15.5　小结
###### 
###### 第16章        REST WEB SERVICE
######         16.1　概述
######                 16.1.1　REST Web Service概念
######                 16.1.2　HTTP协议
######                 16.1.3　HTTPS协议
######                 16.1.4　苹果ATS限制
######         16.2　使用NSURLSession
######                 16.2.1　NSURLSession API
######                 16.2.2　简单会话实现GET请求
######                 16.2.3　默认会话实现GET请求
######                 16.2.4　实现POST请求
######                 16.2.5　下载数据
######         16.3　实例：使用NSURLSession重构MyNotes案例
######                 16.3.1　插入方法
######                 16.3.2　修改方法
######                 16.3.3　删除方法
######         16.4　使用AFNetworking框架
######                 16.4.1　比较ASIHTTPRequest、AFNetworking和MKNetworkKit
######                 16.4.2　安装和配置AFNetworking框架
######                 16.4.3　实现GET请求
######                 16.4.4　实现POST请求
######                 16.4.5　下载数据
######                 16.4.6　上传数据
######         16.5　使用为Swift设计的网络框架：Alamofire
######                 16.5.1　安装和配置Alamofire框架
######                 16.5.2　实现GET请求
######                 16.5.3　实现POST请求
######                 16.5.4　下载数据
######                 16.5.5　上传数据
######         16.6　反馈网络信息改善用户体验
######                 16.6.1　使用下拉刷新控件改善用户体验
######                 16.6.2　使用活动指示器控件
######                 16.6.3　使用网络活动指示器
######         16.7　小结
###### 
###### 第17章        定位服务
######         17.1　定位服务概述
######                 17.1.1　定位服务编程
######                 17.1.2　测试定位服务
######         17.2　管理定位服务
######                 17.2.1　应用启动与停止下的定位服务管理
######                 17.2.2　视图切换下的定位服务管理
######                 17.2.3　应用前后台切换下的定位服务管理
######                 17.2.4　设置自动暂停位置服务
######                 17.2.5　后台位置服务管理
######         17.3　地理信息编码与反编码
######                 17.3.1　地理信息反编码
######                 17.3.2　实例：地理信息反编码
######                 17.3.3　地理信息编码查询
######                 17.3.4　实例：地理信息编码查询
######         17.4　小结
###### 
###### 第18章        苹果地图应用
######         18.1　使用iOS苹果地图
######                 18.1.1　显示地图
######                 18.1.2　显示3D地图
######         18.2　添加标注
######                 18.2.1　实现查询
######                 18.2.2　在地图上添加标注
######         18.3　跟踪用户位置变化
######         18.4　使用程序外地图
######         18.5　小结
###### 
###### 第19章        访问通讯录
######         19.1　通讯录的安全访问设置
######         19.2　使用Contacts框架读取联系人信息
######                 19.2.1　查询联系人
######                 19.2.2　读取单值属性
######                 19.2.3　读取多值属性
######                 19.2.4　读取图片属性
######         19.3　使用Contacts框架写入联系人信息
######                 19.3.1　创建联系人
######                 19.3.2　修改联系人
######                 19.3.3　删除联系人
######         19.4　使用系统提供的界面
######                 19.4.1　选择联系人
######                 19.4.2　显示和修改联系人
######         19.5　小结
###### 
###### 第20章        IOS 10应用扩展
######         20.1　应用扩展概述
######                 20.1.1　iOS 10应用扩展种类
######                 20.1.2　应用扩展工作原理
######                 20.1.3　应用扩展的生命周期
######         20.2　Today应用扩展
######                 20.2.1　使用Today应用扩展
######                 20.2.2　实例：奥运会倒计时牌
######         20.3　开发表情包
######                 20.3.1　iMessage应用
######                 20.3.2　表情包
######                 20.3.3　实例：开发表情包
######         20.4　Message框架
######                 20.4.1　Message框架的主要API
######                 20.4.2　消息布局
######                 20.4.3　消息扩展界面的收缩和展开
######                 20.4.4　消息应用的生命周期
######                 20.4.5　消息会话
######                 20.4.6　实例：高斯模糊滤镜
######         20.5　小结
###### 
###### 第21章        重装上阵的IOS 10用户通知
######         21.1　用户通知概述
######                 21.1.1　通知种类
######                 21.1.2　通知界面
######                 21.1.3　设置通知
######         21.2　开发本地通知
######                 21.2.1　开发本地通知案例
######                 21.2.2　请求授权
######                 21.2.3　通知的创建与发送
######                 21.2.4　通知接收后的处理
######         21.3　开发推送通知
######                 21.3.1　推送通知机理
######                 21.3.2　生成SSL证书
######                 21.3.3　iOS客户端编程
######                 21.3.4　在iOS设备上运行客户端
######                 21.3.5　内容提供者推送通知
######         21.4　小结
###### 
###### 第22章        找出程序中的BUG——调试
######         22.1　Xcode调试工具
######                 22.1.1　定位编译错误
######                 22.1.2　查看和显示日志
######                 22.1.3　设置和查看断点
######                 22.1.4　调试工具
######                 22.1.5　输出窗口
######                 22.1.6　变量查看窗口
######                 22.1.7　查看线程
######         22.2　LLDB调试工具
######                 22.2.1　断点命令
######                 22.2.2　观察点命令
######                 22.2.3　查看变量和计算表达式命令
######         22.3　日志与断言输出
######                 22.3.1　使用NSLog函数
######                 22.3.2　使用断言
######         22.4　异常栈报告分析
######                 22.4.1　跟踪异常栈
######                 22.4.2　分析栈报告
######         22.5　在iOS设备上调试
######                 22.5.1　Xcode设置
######                 22.5.2　设备设置
######         22.6　Xcode设备管理工具
######                 22.6.1　查看设备上的应用程序
######                 22.6.2　设备日志
######         22.7　小结
###### 
###### 第23章        IOS测试驱动与单元测试
######         23.1　测试驱动的软件开发概述
######                 23.1.1　测试驱动的软件开发流程
######                 23.1.2　测试驱动的软件开发案例
######                 23.1.3　iOS单元测试框架
######         23.2　使用XCTest测试框架
######                 23.2.1　添加XCTest到工程
######                 23.2.2　编写XCTest测试方法
######                 23.2.3　运行测试用例目标
######                 23.2.4　分析测试报告
######         23.3　异步单元测试
######         23.4　性能测试
######                 23.4.1　测试用例代码
######                 23.4.2　分析测试结果
######         23.5　小结
###### 
###### 第24章        IOS应用UI测试
######         24.1　UI测试概述
######         24.2　添加UI测试到工程
######                 24.2.1　创建工程时添加UI测试框架
######                 24.2.2　在现有工程中添加UI测试用例目标
######         24.3　录制脚本
######                 24.3.1　录制之前的准备
######                 24.3.2　录制过程
######                 24.3.3　修改录制脚本
######         24.4　访问UI元素
######                 24.4.1　UI元素的层次结构树
######                 24.4.2　UI测试中相关API
######         24.5　表示逻辑组件测试最佳实践
######                 24.5.1　备忘录查询操作
######                 24.5.2　增加备忘录操作
######                 24.5.3　删除备忘录操作
######                 24.5.4　显示备忘录详细信息操作
######         24.6　小结
###### 
###### 第25章        让你的程序“飞”起来—— 性能优化
######         25.1　内存优化
######                 25.1.1　内存管理
######                 25.1.2　使用Analyze工具检查内存泄漏
######                 25.1.3　使用Instruments工具检查内存泄漏
######                 25.1.4　使用Instruments工具检查僵尸对象
######                 25.1.5　autorelease的使用问题
######                 25.1.6　响应内存警告
######         25.2　优化资源文件
######                 25.2.1　图片文件优化
######                 25.2.2　音频文件优化
######         25.3　延迟加载
######                 25.3.1　资源文件的延迟加载
######                 25.3.2　故事板文件的延迟加载
######                 25.3.3　XIB文件的延迟加载
######         25.4　数据持久化的优化
######                 25.4.1　使用文件
######                 25.4.2　使用SQLite数据库
######                 25.4.3　使用Core Data
######         25.5　可重用对象的使用
######                 25.5.1　表视图中的可重用对象
######                 25.5.2　集合视图中的可重用对象
######                 25.5.3　地图视图中的可重用对象
######         25.6　并发处理
######                 25.6.1　一些概念
######                 25.6.2　主线程阻塞问题
######                 25.6.3　选择NSThread、NSOperation还是GCD
######                 25.6.4　GCD技术
######         25.7　小结
###### 
###### 第26章        管理好你的程序代码——代 码版本控制
######         26.1　概述
######                 26.1.1　版本控制历史
######                 26.1.2　基本概念
######         26.2　Git代码版本控制
######                 26.2.1　服务器搭建
######                 26.2.2　Gitolite服务器管理
######                 26.2.3　Git常用命令
######                 26.2.4　Git分支
######                 26.2.5　Git协同开发
######                 26.2.6　Xcode中Git的配置与使用
######         26.3　GitHub代码托管服务
######                 26.3.1　创建和配置GitHub账号
######                 26.3.2　创建代码库
######                 26.3.3　删除代码库
######                 26.3.4　派生代码库
######                 26.3.5　管理组织
######         26.4　小结
###### 
###### 第27章        项目依赖管理
######         27.1　使用CocoaPods工具管理依赖
######                 27.1.1　安装CocoaPods
######                 27.1.2　搜索库
######                 27.1.3　项目与第三方库搭配形式
######                 27.1.4　实例：静态链接库形式管理依赖
######                 27.1.5　实例：框架形式管理依赖
######         27.2　使用Carthage工具管理依赖
######                 27.2.1　安装Carthage
######                 27.2.2　项目与第三方库搭配形式
######                 27.2.3　Cartfile文件
######                 27.2.4　实例：重构MyNotes依赖关系
######         27.3　小结
###### 
###### 第28章        把应用放到APP STORE上
######         28.1　收官
######                 28.1.1　在Xcode 中添加图标
######                 28.1.2　在Xcode中添加启动界面
######                 28.1.3　调整Identity和Deployment Info属性
######         28.2　为发布进行编译
######                 28.2.1　创建开发者证书
######                 28.2.2　创建App ID
######                 28.2.3　创建描述文件
######                 28.2.4　发布编译
######         28.3　发布上架
######                 28.3.1　创建应用
######                 28.3.2　应用定价
######                 28.3.3　基本信息输入
######                 28.3.4　上传应用
######                 28.3.5　提交审核
######         28.4　常见审核不通过的原因
######                 28.4.1　功能问题
######                 28.4.2　用户界面问题
######                 28.4.3　商业问题
######                 28.4.4　不当内容
######                 28.4.5　其他问题
######         28.5　小结
###### 
###### 第29章        IOS开发项目实战—— 2020东京奥运会应用开发及 APP STORE发布
######         29.1　应用分析与设计
######                 29.1.1　应用概述
######                 29.1.2　需求分析
######                 29.1.3　原型设计
######                 29.1.4　数据库设计
######         29.2　任务1：创建应用工程
######                 29.2.1　迭代1.1：创建工程
######                 29.2.2　迭代1.2：发布到GitHub
######         29.3　任务2：数据库与数据持久化逻辑组件开发
######                 29.3.1　迭代2.1：编写数据库DDL脚本
######                 29.3.2　迭代2.2：插入初始数据到数据库
######                 29.3.3　迭代2.3：数据库版本控制
######                 29.3.4　迭代2.4：配置数据持久化逻辑组件
######                 29.3.5　迭代2.5：编写实体类
######                 29.3.6　迭代2.6：编写DAO类
######                 29.3.7　迭代2.7：数据库帮助类DBHelper
######                 29.3.8　迭代2.8：发布到GitHub
######         29.4　任务3：表示逻辑组件开发
######                 29.4.1　迭代3.1：使用资源目录管理图片和图标资源
######                 29.4.2　迭代3.2：根据原型设计初步设计故事板
######                 29.4.3　迭代3.3：“首页”模块
######                 29.4.4　迭代3.4：“比赛项目”模块
######                 29.4.5　迭代3.5：“比赛日程”模块
######                 29.4.6　迭代3.6：“倒计时”模块
######                 29.4.7　迭代3.7：“关于我们”模块
######                 29.4.8　迭代3.8：发布到GitHub
######         29.5　任务4：收工
######                 29.5.1　迭代4.1：添加图标
######                 29.5.2　迭代4.2：设计和添加启动界面
######                 29.5.3　迭代4.3：性能测试与改善
######                 29.5.4　迭代4.4：发布到GitHub
######                 29.5.5　迭代4.5：在App Store上发布应用
######         29.8　小结
###### 
