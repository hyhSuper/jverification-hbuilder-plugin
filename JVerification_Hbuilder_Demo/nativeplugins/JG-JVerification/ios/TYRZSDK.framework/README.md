#
版本号:5.3.11
(在基础版本5392上进行大版本优化)
1、支持联通取号
2、国际化后的bundleId获取代码逻辑优化（彻底解决103101的问题）
3、隐私条款支持自定义
4、隐私条款支持内容自定义alignment
5、支持授权界面弹出的动画方式
6、标题栏、隐私栏、一键登录按钮、切换账号、slogan的字体大小、颜色、文案内容都支持更改
      配置model属性为NSMutableAttributedString类,分别为：navText、privacyText、logBtnText、switchAccText、sloganText
8、号码栏支持x轴偏移量设置
9、偏移量改为NSNumber类型,解决设置0无效，要设置0.01的问题
10、一键登录API方法新增取号回调成功的block
11、登录按钮支持大小设置（宽必须大于屏幕宽度一半,高必须大于40,避免设置过小如同隐藏）
12、隐私条款支持保留《默认条款》以外的自定义设置，并支持内容居中和居左设置属性为privacieAlignment
13、checkBox支持大小设置
14、修复异网显示登录时有缓存的情况下依然取号的问题
15、隐藏导航栏时可以设置状态栏着色样式
16、弹窗模式
17、checkbox大小设置不受限制
18、添加授权界面的dimiss方法
19、修复隐私登录在弱网情况下超时不准确的问题