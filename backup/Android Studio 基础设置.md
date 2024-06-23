### 1.log日志的各种颜色值和设置方法：

> Editor -> color scheme -> android logcat

~~~
绿色 009113  00FF29

克莱因蓝 (0,47,167)     #002fa7
克莱因红 (215,0,15)     #d7000f
蒂芙尼蓝 (129,216,208)  #81D8D0
爱马仕橙 (255,119,15)   #FF770F
勃艮第红 (71,0,36)      #470024
马尔斯绿 (1,132,127)    #01847f
申布伦黄 (251,210,106)  #FBD26A
范戴克棕 (73,45,34)     #492D22
普鲁士蓝 (0,49,83)      #003153
黄支子色 (255,217,86)   #FFD956

提香红 (208,72,72)     #D04848
中国红 (216,44,22)     #D82C16
青春绿 (140,211,83)    #8CD353
淡蕊香 (238,72,102)    #EE4866
紫罗兰 (128,0,128)     #800080
红宝石 (255,85,0)      #FF5500
~~~

#### RGB颜色值与十六进制颜色码转换工具

> <https://www.sioe.cn/yingyong/yanse-rgb-16/>

    Log级别		色值		我的设置
    VERBOSE		BBBBBB		0096ee
    DEBUG		0070BB		00FF29
    INFO		48BB31		f5fdff
    WARN		BBBB23		f6fd18
    ERROR		FF0006		FF1A01
    ASSERT		8F0005  	009113

### 2.logcat中如何过滤当前app打开的页面activity：

> 在logcat的过滤器中输入 displayed 即可展示当前app打开的页面activity

### 3.代码中注释的颜色和设置方法：

> Editor -> color scheme -> java -> comments  
> Editor -> color scheme -> kotlin -> comments   
> Editor -> color scheme -> xml -> comment   
> 设置颜色：#00FF29

### 4.自动生成静态常量或者局部变量时添加前缀：

> Editor -> code style -> java -> Code Generation
> -> Field(name prefix) 改为 m ; Static field(name prefix) 改为 s

### 5.模版代码编写：

> Editor -> Live Templates -> 点击右侧加号添加 Template Group (wyong) -> 选中wyong，点击右侧加号 添加 Live
> Template

> eg:     
> 类注释：classComment     
> 描述：per activity header comment
>> 选择底部 change 勾选 java kotlin，点击 Edit Variables 选择对应变量。
> ~~~
>   /**
>    * @author  $user$
>    * @time    $date$ $time$
>    * @desc
>    *
>    */
> ~~~

> eg:     
> log日志：logd     
> 描述：wyong log debug
>> 选择底部 change 勾选 java kotlin。
> ~~~
> LogUtils.d("WYong", "");    
> ~~~

### 6.新建类时在类头部自动添加注释：

> Editor -> File and Code Templates -> Includes -> File Header

~~~
eg:
   /**
    * <pre>
    *     author : WYong
    *     e-mail : 923275116@qq.com
    *     time   : ${DATE} ${HOUR}:${MINUTE}
    *     desc   :
    * </pre>
    */
~~~