# dazhong_spider_font_svg
大众点评详情页采集（破解css文字映射反爬）可用时间至2020-01-21

项目博客地址（思路讲解）：https://blog.csdn.net/qq_43548498/article/details/104061680

#### 注意：

1.spider_main需要自定义 代理 建议使用代理池

2.spider_main需要定义待采集url队列 

3.自定义cookie

4.固定ip 账号不能过快进行采集 采集过快会触发验证码。建议使用多ip 多账号进行采集


#### 功能：

1.集合多线程采集

2.自定义每个店铺的起始采集页数 会自动采集全部评论数据。

3.捕获大部分报错 并重试
